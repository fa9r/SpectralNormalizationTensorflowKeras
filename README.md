# SpectralNormalizationTensorflowKeras
Spectral Normalization for tf.keras.
This repo contains minor adjustments to the Keras implementation SpectralNormalizationKeras (https://github.com/IShengFang/SpectralNormalizationKeras) to work with tensorflow.keras.

This is useful, because some TF functionalities (like efficient data loading) only work with tf.keras, and tf.keras and keras layers cannot be combined.

## Changes
* All input_dim are casted to int (See this pull request: https://github.com/IShengFang/SpectralNormalizationKeras/pull/4).
* Imports are changed from keras to tf.python.keras.

## Usage
* Clone the SpectralNormalizationKeras repository (https://github.com/IShengFang/SpectralNormalizationKeras)
* Replace SpectralNormalizationKeras/SpectralNormalizationKeras.py with the corresponding file in this repository (SpectralNormalizationTensorflowKeras/SpectralNormalizationKeras.py)
