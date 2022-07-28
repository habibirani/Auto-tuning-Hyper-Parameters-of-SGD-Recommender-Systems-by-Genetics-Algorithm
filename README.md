# Auto-tuning Hyper-Parameters of SGD RS by Genetics Algorithm
This project contains the source code used to evaluate the performance of GFASGD algorithm.

The source code has been structured has follows:

- **Preprocessing:** we only save the defined entries in sparse coordinate format. The dataset is divided into two sets, i.e., train and test sets.

- **Hyperparameter optimisation:** In this step, we propose a genetic algorithm to tune the hyperparameters automatically.

- **Training:** In this step, two primitive feature matrices, i.e., P and Q are initialized randomly using a uniform distribution.

- **Evaluation:** In this step, the MF model is evaluated on a test dataset based on the defined metric (RMSE)


Implementing the proposed genetic algorithm on two datasets (MovieLens 100K and MovieLens 1M) verifies the assertion about the performance. The same code has been used to perform experiments within MovieLens100K and MovieLens1M datasets.

