# Environmental Sensor Placement with Convolutional Gaussian Neural Processes
This repository provides [the Jupyter Notebook](https://github.com/tom-andersson/EDS2023-convgnp-sensor-placement/blob/main/paper_plots.ipynb) used to generate all the figures in the paper ['Environmental Sensor Placement with Convolutional Gaussian Neural Processes' paper]([url](https://doi.org/10.1017/eds.2023.22)) published in _Environmental Data Science_ and presented at the _Climate Informatics_ 2022 conference. [1]

The paper results were generated with an old research codebase, which was subsequently refactored and extended into a vibrant open-source Python package, [DeepSensor](https://github.com/alan-turing-institute/deepsensor/tree/main).

DeepSensor implements all the key data processing, neural process modelling, and active learning functionality used for the paper, but with a much more flexible interface that enables applying this research to any `xarray` or `pandas` data. The package has been used by a growing community of researchers for a range of environmental ML applications.

DeepSensor also has substantial documentation. In particular, see the [active learning](https://alan-turing-institute.github.io/deepsensor/user-guide/active_learning.html) and [acquisition functions](https://alan-turing-institute.github.io/deepsensor/user-guide/acquisition_functions.html) pages of the User Guide, and the [active learning API reference](https://alan-turing-institute.github.io/deepsensor/reference/active_learning/algorithms.html).

Unfortunately though, because I changed jobs soon after the paper was published, I did not have time to clean up the old research codebase nor reproduce the results with DeepSensor. However, please raise an issue if there is anything in particular you would like to see, e.g. code to download data for the paper or implement the GP baselines.

[1] Andersson, T.R., Bruinsma, W.P., Markou, S., Requeima, J., Coca-Castro, A., Vaughan, A., Ellis, A.-L., Lazzara, M., Jones, D.C., Hosking, J.S., Turner, R.E., 2023. Environmental Sensor Placement with Convolutional Gaussian Neural Processes. [https://doi.org/10.48550/arXiv.2211.10381](https://doi.org/10.1017/eds.2023.22)


