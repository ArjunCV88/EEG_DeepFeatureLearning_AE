# EEG_DeepFeatureLearning_AE

Dataset: DEAP http://www.eecs.qmul.ac.uk/mmv/datasets/deap/

LayerVisualization3D file contains:
1. Input reconstruction using CNN 3D Autoencoder.
2. Visualizing training and validation loss using tensorboard.
3. Visualizing intermediate representations of Autoencoder at every layer.

LayerVisualization2D file contains:
1. Input reconstruction using CNN 2D Autoencoder.
2. Visualizing training and validation loss using tensorboard.
3. Computing reconstruction error using several metrics.
4. Visualizing intermediate representations of Autoencoder at every layer.

32SubjectsAE file contains:
1. 32 participant's first video is taken as input for Autoencoder.
2. Input reconstruction using CNN 2D and 3D Autoencoders.
3. Visualizing training and validation loss using tensorboard.
4. Computing reconstruction error using several metrics.
5. Visualizing input, encoded and output layers.

3D_Image file contains:
1. 2 Autoencoder models and their loss evaluation, input/output visualization.
2. Individual bands Autoencoder model construction, loss evaluation and visualizations for input/output layers.
3. 3 band (theta, alpha, beta) Autoencoder model construction, loss evaluation, visualizations for input/output.
4. Computing reconstruction error for 3 band model using various metrics.
