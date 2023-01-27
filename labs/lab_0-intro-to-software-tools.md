## General

Our own CS Prof. Dan Larremore occasionally holds ["How to Science"](https://twitter.com/danlarremore/status/1438306816887246856) seminar series, which include HOW-TOs on:

- Clean Code ([link](https://drive.google.com/file/d/1TraVwRkbkCbHq-s_-NS69ZEbRNwH8XNh/view))
- Data Visualization ([link](https://drive.google.com/file/d/1LouVvISCRlWkItZgzoHcgoU5Q1VyHT4U/view))

You may find them (and references therein) helpful if you want to level up your software skills while taking this course.

Separate note: When you pair up to work on the final project, you may try Google's (free) Colaboratory. Then, you would be able to run a shared notebook on a cloud runtime, in Google Drive. Check out [this page](https://colab.research.google.com/notebooks/intro.ipynb) to learn about Colab's capabilities!

## Probabilistic programming in the Python ecosystem

- Murphy's PML book has a companion repo, which contain notebooks to make all the figures in the book. See [here](https://github.com/probml/pyprobml).
- The repo above uses more low-level libraries such as JAX and TensorFlow, which is nice when we need customization and performance. High-level libraries include [PyMC](https://www.pymc.io/welcome.html) or [PyStan](https://pystan.readthedocs.io/en/latest/), both of which provide interpretable syntax such as `posterior.sample` or `model.fit`.
    - PyMC: This [Rochford article](https://austinrochford.com/posts/intro-prob-prog-pymc.html) contains some good practices of using PyMC. It also recommends 3 books about probabilistic programming (see References).
    - PyStan: Check out Stan's user guide, tutorials, and case studies in their [Documentation](https://mc-stan.org/users/documentation/).
- For visualization, check out [ArviZ](https://python.arviz.org/en/stable/), a dedicated package for exploratory analysis of Bayesian models.
- Python Software Foundation has an annually "Scientific Computing with Python" conference in which the talks are recorded and made public. See, for example, YouTube links from [this page](https://www.scipy2022.scipy.org/tutorials). You may find interesting (and often more advanced!) stuff in there.
- Some talks in the SciPy Conference become [proceedings](https://conference.scipy.org/proceedings/). You may find good stuff such as [this paper](https://conference.scipy.org/proceedings/scipy2018/pdfs/vamvourellis_corvellec.pdf).

## Other fun stuff

- Check out [the distribution zoo](https://ben18785.shinyapps.io/distribution-zoo/).
- Today, let's explore the binomial distribution and its "typical set" when we sample it in high dimension.
    - See Section 3 of this [Stan case study](https://mc-stan.org/users/documentation/case-studies/curse-dims-python.html) on "Typical Sets and the Curse of Dimensionality." (note: we only used the scipy package of Python)
    - For more intuition, check out the "Gaussian soap bubble" phenomenon (subsection 2.3.1.2 & Figure 2.9 of Murphy)

## References

- *Probabilistic Programming and Bayesian Methods for Hackers*, by Cameron Davidson-Pilon. (see [this repo](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers))
- *Bayesian Modeling and Computation in Python*, by Osvaldo Martin, Ravin Kumar, and Junpeng Lao (see [Jupyter Book](https://bayesiancomputationbook.com/welcome.html))
- *Statistical Rethinking: A Bayesian Course with Examples in R and Stan*, by Richard McElreath. (see [book homepage](https://xcelab.net/rm/statistical-rethinking/))

