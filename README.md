# STAT 618 Project
## Implementing Vecchia-Approximated Deep Gaussian Processes

Implements a Vecchia approximated deep Gaussian process (DGP; Sauer, 2022). The
DGP was first proposed by Damianou and Lawrence (2013; AISTATS). Vecchia
approximations originated as a composite likelihood technique (Vecchia, 1988),
and recent work has developed rich theory around using the technique for modeling
in computer experiments and spatial statistics (Katzfuss and Guinness, 2021).

I give a `pytorch`-based implementation of the model. An `R` package by Annie
Sauer is available on [CRAN](https://cran.r-project.org/web/packages/deepgp/vignettes/deepgp.html).

## References

[1] [Saur et al. (2022, JCGS)](https://www.tandfonline.com/doi/full/10.1080/10618600.2022.2129662)

[2] [Damianou and Lawrence (2013, AISTATS)](http://proceedings.mlr.press/v31/damianou13a.html)

[3] [Vecchia (1988, JRSSB)](10.1111/j.2517-6161.1988.tb01729.x)

[4] [Katzfuss and Guinness (2021, Statistical Science)](https://projecteuclid.org/journals/statistical-science/volume-36/issue-1/A-General-Framework-for-Vecchia-Approximations-of-Gaussian-Processes/10.1214/19-STS755.full)