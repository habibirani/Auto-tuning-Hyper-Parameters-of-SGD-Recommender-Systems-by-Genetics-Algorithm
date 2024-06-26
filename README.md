# Auto-tuning Hyper-Parameters of SGD RS by Genetics Algorithm
This project contains the source code used to evaluate the performance of GFASGD algorithm.

Code from the paper titled "Auto-tuning HyperParameters of SGD Matrix Factorization-Based Recommender Systems Using Genetic Algorithm".

Best Student Paper Award of 2022 IEEE International Conference on Omni-layer Intelligent Systems (COINS) [![Conference](https://img.shields.io/badge/Conference-2022-008000.svg)](https://ieeexplore.ieee.org/abstract/document/9854956)


## Installation

To set up the project clone the repository and install the required packages:

```bash
git clone https://github.com/Habibirani/Auto-tuning-Hyper-Parameters-of-SGD-Recommender-Systems-by-Genetics-Algorithm.git
cd Auto-tuning-Hyper-Parameters-of-SGD-Recommender-Systems-by-Genetics-Algorithm
conda env create -f environment.yml

```

![Flowchart](Img/Flowchart.png)

The source code has been structured has follows:

- **Preprocessing:** we only save the defined entries in sparse coordinate format. The dataset is divided into two sets, i.e., train and test sets.

- **Hyperparameter optimisation:** In this step, we propose a genetic algorithm to tune the hyperparameters automatically.

- **Training:** In this step, two primitive feature matrices, i.e., P and Q are initialized randomly using a uniform distribution.

- **Evaluation:** In this step, the MF model is evaluated on a test dataset based on the defined metric (RMSE)


Implementing the proposed genetic algorithm on two datasets (MovieLens 100K and MovieLens 1M) verifies the assertion about the performance. The same code has been used to perform experiments within MovieLens100K and MovieLens1M datasets.


<!-- CONTRIBUTING -->
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


<!-- CITATION -->
## Citation


```bibtex
@inproceedings{irani2022auto,
  title={Auto-tuning HyperParameters of SGD Matrix Factorization-Based Recommender Systems Using Genetic Algorithm},
  author={Irani, Habib and Elahi, Fatemeh and Fazlali, Mahmood and Shahsavari, Mahyar and Farahani, Bahar},
  booktitle={2022 IEEE International Conference on Omni-layer Intelligent Systems (COINS)},
  pages={1--7},
  year={2022},
  organization={IEEE}
}
```
