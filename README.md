# Deep Learning Experiment 2

## Comparative Study of Activation Functions and Optimization Algorithms in Deep Learning

### Student Details

* **Name:** Harshitha
* **Roll No:** 24BAD034
* **Experiment No:** 2

## Aim

To analyze the impact of different activation functions and optimization algorithms on the performance of Artificial Neural Networks (ANNs) and to learn best practices for managing deep learning experiments using cloud-based tools and version control.

## Dataset

**MNIST Handwritten Digit Dataset**

The MNIST dataset contains handwritten digit images belonging to 10 classes, from 0 to 9.

## Software and Tools Used

* Python
* TensorFlow / Keras
* Google Colab
* Google Drive
* GitHub
* Matplotlib
* NumPy

## Task A — Visualization of Activation Functions

The following activation functions were implemented and visualized:

* Sigmoid
* Tanh
* ReLU

Their output ranges, saturation regions, gradient behavior, computational efficiency, and typical applications were studied.

## Task B — Performance Comparison of Activation Functions

Identical ANN architectures were trained using:

* Sigmoid
* Tanh
* ReLU

The following performance measures were compared:

* Training accuracy
* Validation accuracy
* Training loss
* Validation loss
* Test accuracy

Graphs were plotted to compare the performance of the activation functions.

## Task C — Comparison of Optimization Algorithms

The same ANN architecture with ReLU activation was trained using:

* SGD
* Momentum
* RMSProp
* Adam

The following parameters were compared:

* Training loss
* Validation loss
* Training accuracy
* Validation accuracy
* Test accuracy
* Convergence behavior

Loss and accuracy graphs were plotted against the number of epochs.

## Task D — Experiment Management

The experiment was managed using:

* **Google Colab** for writing and executing the deep learning code.
* **Google Drive** for storing the notebook and trained model.
* **GitHub** for storing the code, README file, and maintaining version history.

## Model Architecture

The ANN used for the experiment consists of:

1. Flatten layer
2. Dense layer with 128 neurons
3. Activation function
4. Dense output layer with 10 neurons
5. Softmax activation for classification

## Results

The experiments were used to compare the effect of different activation functions and optimization algorithms on ANN performance.

The obtained accuracy, loss, and convergence results are available in the accompanying Google Colab notebook.

## Conclusion

The experiment demonstrates that activation functions and optimization algorithms have a significant effect on neural network training and performance. Different combinations can result in different convergence behavior, accuracy, and loss values.

## Files

* `Deep_Learning_Experiment_2.ipynb` — Google Colab experiment notebook
* `README.md` — Experiment documentation
* `activation_comparison_model.keras` — Saved trained model
