This program demonstrates the usage of Tensorflow using GPU acceleration to train a Recurring Neural Network (RNN) model. The tasks performed in this program are:
- A short overview of RNN and basics of how they work
- Setting up a custom Jupyter environment to natively use GPU acceleration, using tensorflow 2.10 and python 3.10, the last version with native GPU acceleration support (later versions need WSL)
- Verifying GPU usage
- Performance comparison between default (CPU) and GPU acceleration
- Training of model on example dataset (Sherlock Holmes - the final problem)
- Use of model to predict next words based on initial sentence.

All steps and workflows are detailed in the notebook.

Project implemented on a PC with AMD Ryzen 7840HS and Nvidia RTX 4060 GPU, using CUDA (cuDNN) libraries.

Future ideas: Use a much larger dataset to uncover challenges pertaining to memory management and efficient utilization of resources. Ideally, V2 can have the entire canon of Sherlock.
