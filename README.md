# 🌱 Plant Disease Classification Using Deep Learning

This project is a Flask-based web application that uses a Convolutional Neural Network (CNN) to classify plant diseases into three categories: **Healthy**, **Powdery**, and **Rust**. It provides a simple interface for uploading plant images and receiving predictions.

---

## 📑 Table of Contents

1. [Features](#features)
2. [File Structure](#file-structure)
   - [Key Files](#key-files)
3. [Installation](#installation)
   - [Prerequisites](#prerequisites)
   - [Steps to Clone the Repository](#steps-to-clone-the-repository)
   - [Install Dependencies](#install-dependencies)
4. [Running the Application](#running-the-application)
5. [Dataset Information](#dataset-information)
6. [Technologies Used](#technologies-used)
7. [Team Members](#team-members)
8. [Contributing](#contributing)
9. [License](#license)
10. [Acknowledgments](#acknowledgments)

---

## 🌟 Features

- **Deep Learning Model**: Utilizes a trained CNN for accurate plant disease classification.
- **User Interface**: Easy-to-use web interface built with Flask.
- **Dataset**: Structured dataset for training, validation, and testing.
- **Expandable**: You can extend the model to classify additional diseases.

---

## 📂 File Structure

```
├───.ipynb_checkpoints
├───Dataset
│   ├───Test
│   │   └───Test
│   │       ├───Healthy
│   │       ├───Powdery
│   │       └───Rust
│   ├───Train
│   │   └───Train
│   │       ├───Healthy
│   │       ├───Powdery
│   │       └───Rust
│   └───Validation
│       └───Validation
│           ├───Healthy
│           ├───Powdery
│           └───Rust
├───static
│   ├───css
│   └───js
│       └───vendor
├───templates
└───uploads
```

### 📁 Key Files

- `app.py`: The main Flask application.
- `Dataset/`: Contains training, testing, and validation data organized into categories.
- `static/`: Contains static resources such as CSS and JavaScript.
- `templates/`: Contains HTML templates for the web interface.
- `uploads/`: Stores uploaded images for prediction.

---

## ⚙️ Installation

### 🧾 Prerequisites

Ensure you have the following installed:
- Python 3.8+
- pip (Python package installer)
- Git

### 🛠️ Steps to Clone the Repository

1. Open your terminal or command prompt.
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Plant-Disease-Classification.git
   ```
3. Navigate into the project directory:
   ```bash
   cd Plant-Disease-Classification
   ```

### 📦 Install Dependencies

1. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Running the Application

1. Ensure the `model1.h5` file (trained CNN model) is in the project directory.
2. Start the Flask server:
   ```bash
   python app.py
   ```
3. Open your web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```
4. Upload an image of a plant leaf and view the predicted disease.

---

## 📊 Dataset Information

- The dataset is divided into three categories:
  - **Healthy**
  - **Powdery**
  - **Rust**
- Each category is further split into training, testing, and validation datasets.

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow/Keras**: For building and training the CNN model.
- **Flask**: For the web application.
- **HTML/CSS/JavaScript**: For the front-end interface.

---

## 👥 Team Members

- **Kishan**: [GitHub Profile](https://github.com/km1000101)
- **Mayur**: [GitHub Profile](https://github.com/Mayurx75)
- **Srujan**: [GitHub Profile](https://github.com/SrujanVN)

---

## 🤝 Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

### Future Contributions
- Improve the CNN model by adding more categories of plant diseases.
- Enhance the front-end user interface with advanced visualization tools.
- Add real-time prediction capabilities using streaming input.

---

## 🙏 Acknowledgments

- A heartfelt thanks to our mentor, [**Dr. Victor A.I**](https://github.com/Victor-Ikechukwu), for his invaluable guidance and support throughout this project.
- Special recognition to our team members [**Kishan**](https://github.com/km1000101), [**Mayur**](https://github.com/Mayurx75), and [**Srujan**](https://github.com/SrujanVN) for their dedicated contributions and teamwork.
- Gratitude to open-source contributors and dataset providers for enabling this project.

