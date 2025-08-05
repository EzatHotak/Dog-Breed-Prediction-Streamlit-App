# Dog Breed Classification using CNN

## 📌 Project Overview

In this project, we demonstrate how to use **Keras** and **TensorFlow** to build, train, and test a **Convolutional Neural Network (CNN)** capable of identifying the **breed of a dog** in a supplied image.

This is a **supervised learning** problem, specifically a **multiclass classification** task.

## 🧠 Key Features

- 🐶 Classifies multiple dog breeds from images
- 🧠 Uses CNN architecture for high accuracy
- 📈 Includes training, validation, and testing phases
- 🔄 Supports model saving and loading

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV or PIL (for image processing)
- Matplotlib (for visualization)

## 🚀 Use Cases

- Pet breed recognition applications
- Veterinary tech support tools
- Dog shelter and adoption filtering systems

## 🗂️ Project Structure

```
├── dataset/                # Training and test images (organized by breed)
├── models/                 # Saved CNN models
├── src/                    # Source code
│   ├── train_model.py      # Script to train the CNN
│   ├── predict_breed.py    # Script to test the CNN
│   └── utils.py            # Helper functions
├── requirements.txt        # Dependencies list
└── README.md               # Project documentation
```

## 📥 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/dog-breed-classifier.git
   cd dog-breed-classifier
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## 📊 Dataset

Make sure your dataset is structured like this:

```
dataset/
├── beagle/
│   ├── img1.jpg
│   └── img2.jpg
├── labrador/
│   ├── img1.jpg
│   └── img2.jpg
...
```

## 👨‍💼 Contributors

- [Your Name](https://github.com/EzatHotak)

## 📄 License

This project is licensed under the MIT License.

---

> 🐾 This model helps identify dog breeds with the power of deep learning.
