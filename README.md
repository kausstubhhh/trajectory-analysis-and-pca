# Trajectory Modelling and Shape Analysis

This project explores how different regression techniques and dimensionality reduction methods can be used to model and understand structured data.

## Overview

The work is divided into two main parts:

### 1. Trajectory Modelling

A 2D trajectory was analysed over time using different basis function approaches:

* Polynomial regression
* Combination of trigonometric and polynomial basis functions

The goal was to understand how model complexity affects the quality of fit and to identify suitable basis functions for different types of patterns (linear trends, periodic behaviour, and non-linear growth).

### 2. Shape Analysis using PCA

A high-dimensional dataset representing 3D shapes was analysed.

* Each sample represents a 3D structure encoded in a high-dimensional space
* Principal Component Analysis (PCA) was used to reduce dimensionality
* Shapes were reconstructed using a small number of principal components

This demonstrates how complex structures can be represented efficiently in lower-dimensional space.

## Key Observations

* Simple models tend to underfit complex trajectories
* Combining basis functions helps capture both trends and oscillations
* High-dimensional shape data contains strong redundancy
* A small number of principal components can preserve most of the structure

## Tools Used

* Python
* NumPy
* Matplotlib
* Scikit-learn

## Files

* `Question.ipynb` – main notebook containing experiments and visualisations
* `.npy` files – datasets used for modelling
* `trajectory.csv` – time-series trajectory data

---

This project focuses on understanding model behaviour rather than just achieving numerical accuracy.
