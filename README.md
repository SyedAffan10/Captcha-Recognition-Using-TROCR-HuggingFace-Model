# CAPTCHA Recognition Using TrOCR

A machine learning project that recognizes text in CAPTCHA images using the **TrOCR (Transformer-based Optical Character Recognition)** model from HuggingFace.

## 📁 Project Structure

```
├── app.ipynb                    # Main Jupyter notebook with implementation
├── requirements.txt             # Python dependencies
├── model/
│   └── ocr_model_v1.h5         # Trained OCR model
└── sample images/              # Sample CAPTCHA images for testing
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Installation

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook app.ipynb
```

## 📦 Key Dependencies

- **transformers** - HuggingFace TrOCR model
- **torch/tensorflow** - Deep learning framework
- **pillow** - Image processing
- **numpy** - Numerical computing

## 🎯 Features

- CAPTCHA text recognition using pre-trained TrOCR model
- Support for image preprocessing
- Easy-to-use Jupyter notebook interface
- Sample images included for testing

## 📝 Usage

Run the cells in `app.ipynb` to:
1. Load sample CAPTCHA images
2. Process and preprocess images
3. Run OCR recognition
4. Display results

