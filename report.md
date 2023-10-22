Alphabet Soup Predictive Model Report
Overview

Alphabet Soup, a non-profit organization, aims to streamline its funding decisions by developing a predictive model. The model will assess the likelihood of success for funding applicants. We'll create a binary classification model using machine learning and neural networks to achieve this goal.
Data Preparation


    Data Source: We obtained a dataset of 34,000 funded organizations.

    Processing:
        Encoding categorical variables using one-hot encoding.
        Binning of 'CLASSIFICATION' and 'APPLICATION_TYPE' features to reduce dimensionality.

    Data Split: We divided the dataset into training and testing sets.

    Feature Scaling: StandardScaler was applied to standardize features.

Model Development
Neural Network Architecture

    Model Structure:
        Input features: Variable count.
        Hidden layers: Three layers with 12, 10, and 12 neurons.
        Output layer: Single neuron for binary classification.

    Activation Functions: Sigmoid function used for hidden layers.

Model Compilation

    Loss Function: Binary cross-entropy.
    Optimizer: Adam.
    Metrics: Accuracy.

Model Training

    Trained for 50 epochs.

Model Optimization

    Multiple optimization attempts were made:
        Adjusted neuron count and layers.
        Experimented with different activation functions.
        Fine-tuned training parameters.

Model Evaluation

    Model accuracy: Approximately 72.90%.

Model Export

    The model was saved in an HDF5 file for future use.

Conclusion

The predictive model enhances funding decision-making at Alphabet Soup. By accurately assessing the likelihood of success for funding applicants, resources can be allocated effectively, maximizing impact on charitable causes.


Acknowledgments

We thank Alphabet Soup's business team for providing the dataset.
References

    Pandas
    TensorFlow
    Scikit-learn