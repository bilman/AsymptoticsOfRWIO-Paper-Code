# AsymptoticsOfRWIO-Paper-Code
This repository includes samples for the code used in the scientific paper 

*General rogue waves of infinite order: exact properties, asymptotic behavior, and effective numerical computation* [D. Bilman & P. D. Miller, 2024]. 

More explicitly, it includes:

- a Jupyter notebook titled `Painleve2TT.ipynb` that contains all the routines to compute the "potential" $\mathcal{V}(y;\tau)$ associated with the increasing tritronquée solution of Painlevé-II equation:
```math
u^{\prime \prime}(x)=x u(x)+2 u(x)^3-\alpha,
```
with parameter $\alpha=\frac{1}{2}+\mathrm{i}p$, where $p=\frac{1}{2\pi}\ln(1+\frac{|b|^2}{|a|^2})$. Here $a,b\in\mathbb{C}\setminus\lbrace 0\rbrace$ are parameters indexing the family of solutions called *general rogue waves of infinite order*.

- a Jupyter notebook titled `Paper-Code.ipynb` that contains the code samples used in the paper to produce the plots and examples.

- a Jupyter notebook titled `Painleve-Comparison.ipynb` that contains the code samples used in the paper to compute the rogue waves of infinite order in the Painlevé region (the region where transitional asymptotic behavior was established in the paper).