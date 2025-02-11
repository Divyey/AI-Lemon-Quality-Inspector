# AI Lemon Quality Inspector

## Overview

This project automates the visual inspection of lemons using Machine Learning techniques. It classifies lemons based on their quality using image processing and classification models.

## Features

- Image-based lemon quality classification.
- Dataset preprocessing and feature extraction.
- Model training using Logistic Regression.
- Prediction and result storage.
- Visualization of classification results.

## Dataset

The dataset consists of lemon images categorized for training and testing:

- `train_images/` (Training images)
- `test_images/` (Testing images)
- `train_images.csv` (Labels for training images)
- `test_images.csv` (Image filenames for testing)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Divyey/AI-Lemon-Quality-Inspector.git
   cd AI-Lemon-Quality-Inspector
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the classification pipeline:

```python
python main.py
```

## Results

The model achieved:

- **Training Accuracy:** 92.74%
- **Validation Accuracy:** 94.56%
- **Test Accuracy:** 100.00%

Classified results are saved in `lemon_results.csv`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to open issues and pull requests to improve the project.

## Author

[Divyey Arora](https://github.com/Divyey)

