# CNN Hyperparameter Optimization using Genetic Algorithm 🧬🛰️

This repository contains the term project for the **MYZ208: Optimization Techniques** course at **Atatürk University, Artificial Intelligence and Data Engineering** department.

## 📌 Project Overview
Finding the optimal architecture and training parameters for Deep Learning models is a highly non-linear and computationally expensive task. Grid search and random search often fail to find the global optimum efficiently. 

This project implements a **Genetic Algorithm (GA)** to intelligently search the hyperparameter space of a Convolutional Neural Network (CNN). The model is trained and validated on a **Satellite Image Classification** dataset. By using evolutionary mechanics (Selection, Crossover, Mutation, and Elitism), the algorithm successfully avoids local minima and discovers a robust set of parameters.

## 🚀 Features
* **Custom Genetic Algorithm:** Built-in Python to evolve CNN parameters over multiple generations.
* **Optimized Hyperparameters:** Dynamically tunes `learning_rate`, `batch_size`, `optimizer` (Adam vs RMSprop), `activation` functions, and `dense_neurons`.
* **Keras 3 Compatibility:** Utilizes the latest `tf.keras.layers.Input` architecture standards.
* **Performance Tracking:** Automatically visualizes accuracy, loss, convergence comparisons (Basic vs GA), and generational fitness evolution.

## 📊 Dataset
The models are trained on a **Satellite Image Classification** dataset. The images represent various real-world scenarios including different atmospheric conditions, seasonal changes, and complex topographical structures. This natural variance acts as a regularization mechanism, making the hyperparameter optimization crucial for achieving high generalization capabilities.
* Images are resized to `64x64x3` and normalized to the `[0, 1]` range.

## 📈 Results
The Genetic Algorithm successfully improved the baseline CNN model by exploring the hyperparameter space. The GA-optimized model demonstrated a much more stable learning curve without overfitting, proving the efficiency of evolutionary algorithms in deep learning workflows.

| Model | Validation Accuracy |
| :--- | :---: |
| Baseline CNN | ~ 92.59% |
| **GA Optimized CNN** | **~ 95.78%** |

*(Check the `/docs` folder for the detailed academic report and performance graphs in Turkish).*

## 🛠️ Tech Stack
* **Python 3**
* **TensorFlow / Keras** (Deep Learning)
* **NumPy** (Mathematical Operations)
* **Matplotlib** (Data Visualization)

## 👨‍💻 Author
**Seyit Ali Arslan**
* Artificial Intelligence and Data Engineering @ Atatürk University
* [LinkedIn](Senin_Linkedin_Linkin_Buraya) | [GitHub](https://github.com/SeninKullaniciAdin)
