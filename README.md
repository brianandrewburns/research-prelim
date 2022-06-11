# research-prelim

This repository contains my implementation of the experiments replicating [Quantifying Uncertainty in Online Regression Forests](https://jmlr.org/papers/v20/19-006.html).

The experiments are implemented in the Experiments notebook. The figures are generated in the Plots notebook.

Included as submodules are my modifications of River and scikit-garden, two open-source machine learning libraries. The former contains my implementations of OnlineCP and OnlineQRF, and the latter implements the Mondrian Forests baseline to which they are compared. You can view them as separate repositories (with my commit history, etc) here: [River](https://github.com/brianandrewburns/river), [scikit-garden](https://github.com/brianandrewburns/scikit-garden).

The authors' code for the paper is open-source as well, available [here](https://github.com/thvasilo/uncertain-trees-reproducible). My goal with the project was to implement it in an entirely Python-native fashion without relying on the authors' code or any of its Java dependencies. The only code overlap is snippets of some of their plotting code copied over for stylistic integrity.
