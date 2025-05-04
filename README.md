# Understanding Padding, Pooling, and Stride in CNNs using Keras

This repository demonstrates **core concepts of Convolutional Neural Networks (CNNs)** such as **padding**, **pooling**, and **stride** using practical examples in **Keras**.

These foundational techniques are crucial for image processing, feature extraction, and controlling the spatial dimensions in deep learning models.

---

## 📁 Files Included

| File                                                                                                                                          | Description                                                                                                                 |
| :-------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------- |
| [`keras_padding_demo.ipynb`](https://github.com/HaseebUlHassan437/padding_pooling-and-stride-using-keras-/blob/main/keras_padding_demo.ipynb) | Shows how **padding** (`valid` vs `same`) affects output dimensions and feature maps during convolution.                    |
| [`keras_pooling_demo.ipynb`](https://github.com/HaseebUlHassan437/padding_pooling-and-stride-using-keras-/blob/main/keras_pooling_demo.ipynb) | Demonstrates **pooling operations** (MaxPooling and AveragePooling) and how **stride** influences the downsampling process. |

---

## 🧠 Key Concepts Covered

### ✅ Padding

* **Valid Padding**: No padding applied — shrinks output.
* **Same Padding**: Pads input to maintain the same output size.

### ✅ Pooling

* **MaxPooling**: Takes the max value from each window.
* **AveragePooling**: Takes the average value.
* Pooling helps reduce spatial dimensions while retaining important features.

### ✅ Stride

* Controls the **step size** of the filter window.
* Affects how much the feature map is downsampled.

---

## 🛠️ Requirements

* Python 3.x
* Google Colab / Jupyter Notebook
* Libraries:

  * `tensorflow`
  * `keras`
  * `numpy`

Install with:

```bash
pip install tensorflow numpy 
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/HaseebUlHassan437/padding_pooling-and-stride-using-keras-.git
cd padding_pooling-and-stride-using-keras-
```

2. Open the notebooks in **Google Colab** or **Jupyter Notebook**.

3. Run the cells to visually understand how padding, stride, and pooling change the tensor shapes and extracted features.

---

## 📈 Learning Outcomes

* Visualize how padding maintains or shrinks image size.
* Understand the effect of stride on convolutional/pooling layers.
* Compare MaxPooling vs AveragePooling in feature reduction.

---

## 👨‍💻 Author

**Haseeb Ul Hassan**
GitHub: [@HaseebUlHassan437](https://github.com/HaseebUlHassan437)


