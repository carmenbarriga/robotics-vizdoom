# **Vizdoom project**

There is a training file for each experiment. Both are found inside the training folder. Training is done using Pytorch. To perform the training, the training file must be placed inside `ViZDoom/examples/python/`.

- The training file for experiment 1 is `learning/cacodemon.py`.
- The training file for experiment 2 is `learning/health_gathering.py`.
- The training file for experiment 3 is `learning/new_experiment.py`.

There is a test file for evaluating our agents. Both are found inside the test file. To perform the test, the test file must be placed inside `ViZDoom/examples/python/`.

- The test file for experiment 1 is `test/cacodemon_test.py`.
- The test file for experiment 2 is `test/health_gathering_test.py`.
- The test file for experiment 3 is `test/new_experiment_test.py`.

In the models folder are the models with the weights obtained after training.

- `model-doom-cacodemon.pth` contains the model obtained for experiment 1.
- `model-doom-health-gathering.pth` contains the model obtained for experiment 2.
- `model-doom-new-experiment.pth` contains the model obtained for experiment 3.

Models are called when an experiment is tested. For this, the models must be inside the folder `ViZDoom/examples/python/`.
