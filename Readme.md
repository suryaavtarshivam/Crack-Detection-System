AI-Powered Crack Detection System

Overview

The AI-Powered Crack Detection System is a cutting-edge project designed to enhance infrastructure safety by leveraging advanced deep learning techniques for detecting cracks in various surfaces. This project streamlines the entire workflow, from data preparation to prediction, making it an invaluable tool for engineers, facility managers, and researchers.

Features

Efficient Model: Utilizes EfficientNet-B0 for highly accurate crack detection.

Optimized Dataset Handling: Supports real-time image preprocessing, including resizing, normalization, and optional preloading.

Dynamic Training Pipeline: Incorporates advanced optimizers (AdamW), learning rate scheduling, and robust validation to ensure top performance.

User-Friendly Interface: Simple folder selection for data input using a graphical interface.

Scalable and Efficient: Multi-core support for data loading and training.

Requirements

Software

Python 3.8+

PyTorch 1.12+

torchvision 0.13+

pandas

numpy

Pillow

scikit-learn

tkinter

Hardware

GPU recommended (NVIDIA CUDA support) for faster training and inference.

Installation

Clone the repository:

git clone https://github.com/your-repo/ai-crack-detection.git
cd ai-crack-detection

Install the required dependencies:

pip install -r requirements.txt

Verify installation by running:

python main.py

Usage

Dataset Preparation

Organize your dataset into the following folder structure:

/dataset
    /positive
        image1.jpg
        image2.jpg
    /negative
        image1.jpg
        image2.jpg
    /test
        image1.jpg
        image2.jpg

Running the System

Launch the application:

python main.py

Select folders for positive, negative, and test datasets via the graphical interface.

The system will automatically train the model and display predictions for the test dataset.

Project Structure

project-root
├── main.py                  # Entry point for the application
├── model.py                 # Defines the EfficientNet-based model
├── dataset.py               # Custom dataset handling logic
├── utils.py                 # Utility functions for data preparation
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation

Performance

Achieves high accuracy and efficiency with optimized data pipelines and model architecture.

Easily customizable for specific datasets and applications.

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements or bug fixes.
