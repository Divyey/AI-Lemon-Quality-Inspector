# AI-Powered Visual Inspection for Lemon Quality Classification

## Overview
This project automates the visual inspection of lemons using Machine Learning. It classifies lemons based on their quality using image processing and classification algorithms.

## Dataset
The dataset consists of images of lemons categorized into different quality classes. It includes:
- **Train Images:** Used for training the model.
- **Test Images:** Used for evaluating the model.
- **CSV Files:** Metadata containing image file names and labels.

## Project Workflow
1. **Download & Extract Data**: Load images and CSV files.
2. **Feature Extraction**: Convert images into meaningful numerical features.
3. **Model Training**: Train a machine learning model (Logistic Regression, SVM, etc.) for classification.
4. **Prediction & Evaluation**: Classify test images and evaluate performance.
5. **Save Results**: Store classification results in a CSV file.

## Installation
```bash
# Clone the repository
git clone https://github.com/your-username/lemon-quality-inspection.git
cd lemon-quality-inspection

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
from model import train_model, predict

# Train the model
train_model("hiroshima-lemon/train_images", "hiroshima-lemon/train_images.csv")

# Predict on test data
predict("hiroshima-lemon/test_images", "hiroshima-lemon/test_images.csv")
```

## Results
- Classification accuracy: **XX%**
- Example predictions:

![Sample Results](results/sample.png)

## Technologies Used
- Python
- NumPy, Pandas, Matplotlib
- Scikit-learn
- Mahotas (for image processing)
- Logistic Regression, SVM, KNN

## Future Improvements
- Improve classification accuracy with CNNs
- Deploy as a web application
- Add real-time image processing capabilities

## License
This project is licensed under the MIT License.

## Contributors
- **Your Name** - [GitHub](https://github.com/Divyey)

