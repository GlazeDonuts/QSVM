# QSVM
This repository contains a basic implementation of a Quantum Support Vector Machine (QSVM) for binary classification.

The QSVM algorithm takes the classical machine learning algorithm and performs the support vector machine on a quantum circuit in order to be efficiently processed on a quantum computer.

The QSVM module from Qiskit Aqua, was trained on two datasets, one ad-hoc and another real-world dataset for breast cancer.

Below is a dimensionally reduced (via PCA) plot of the breast cancer dataset alongside the learned kernel used to perform binary classificatio using support vector mechanism.
<p align="center">
<img src="https://github.com/GlazeDonuts/QSVM/blob/master/resources/bcancer.png?raw=True"/>
<img src="https://github.com/GlazeDonuts/QSVM/blob/master/resources/kernel.png?raw=True"/>
</p>

Accuracies more than 99% were achieved.
