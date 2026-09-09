# Potato Leaf Disease Detection

Potato Leaf Disease Detection is a deep learning-based project designed to identify diseases in potato leaves using image analysis. The main goal is to detect whether a potato leaf is healthy or infected and to classify the disease type accurately, such as Early Blight, Late Blight, or Healthy.

## Project Overview

This project uses artificial intelligence and computer vision techniques to assist in potato leaf disease detection. By training a model on a labeled dataset, the system can diagnose diseases quickly, efficiently, and cost-effectively.

When a farmer, researcher, or user uploads an image of a potato leaf, the model can classify it into one of the following categories:

- Early Blight
- Healthy
- Late Blight

## Objectives

- Detect potato leaf diseases from plant images
- Train and evaluate a dataset-driven model
- Provide fast and accurate disease classification results
- Support agricultural productivity and crop protection

## Dataset

The dataset used in this project is designed for potato leaf disease detection. It contains three main classes:

- Early Blight
- Healthy
- Late Blight

The folder structure is as follows:

```text
Dataset/
├── New folder/
│   ├── Potato___Early_blight/
│   ├── Potato___healthy/
│   └── Potato___Late_blight/
├── PLD_3_Classes_256/
│   ├── Training/
│   │   ├── Early_Blight/
│   │   ├── Healthy/
│   │   └── Late_Blight/
│   ├── Validation/
│   │   ├── Early_Blight/
│   │   ├── Healthy/
│   │   └── Late_Blight/
│   └── Testing/
│       ├── Early_Blight/
│       ├── Healthy/
│       └── Late_Blight/
```

## Project Structure

```text
Potato_Leaf_Disease_Detection/
├── README.md
├── Dataset/
│   ├── New folder/
│   └── PLD_3_Classes_256/
├── Research Paper/
│   └── related research PDFs
└── (future model scripts, notebooks, training files)
```

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Pandas
- scikit-learn

## Typical Workflow

1. Collect and organize the dataset
2. Load images and preprocess them
3. Resize, normalize, and augment images
4. Train a CNN or machine learning model
5. Validate and test the trained model
6. Generate disease classification results

## Setup Instructions

### Prerequisites

- Python 3.9+
- pip
- virtual environment (recommended)

### Install Dependencies

```bash
pip install tensorflow opencv-python numpy pandas matplotlib scikit-learn
```

### Run the Project

```bash
python train.py
```

If using Jupyter Notebook:

```bash
jupyter notebook
```

## Expected Outcome

This project aims to build a model that can accurately identify the disease type of a potato leaf from an image. This can help farmers, researchers, and agricultural stakeholders detect issues early and take timely action.

## Benefits

- Fast disease detection
- Improved agricultural productivity
- Early treatment and prevention
- Automated monitoring system

## Future Improvements

- Add more datasets
- Use larger CNN or transfer learning models
- Develop a web or mobile application
- Enable real-time disease detection
- Deploy the model in a production environment

## Research References

This project includes relevant research papers and reference documents in the `Research Paper/` folder. These materials can be used to improve the model and support further research.

## License

This project is created for educational and research purposes. A license can be added based on future usage requirements.

## Author

Potato Leaf Disease Detection Project

---

This README provides a clear overview of the project goals, dataset, structure, and setup instructions in a clean and professional format.
