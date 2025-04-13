# 🖼️ Neural Style Transfer with TensorFlow

This project implements Neural Style Transfer using TensorFlow. The model blends the **content** of one image with the **style** of another to generate a unique artistic image.

## 🎯 Goal

Generate a stylized image by combining the *content image* (structure) with the *style image* (artistic texture).

## 🛠️ Technologies
- Python 3
- TensorFlow 2.x
- Matplotlib
- NumPy

## 📁 Files
- `style_transfer.py`: Main script that performs neural style transfer.
- `README.md`: Project documentation.

## 🖼️ Example
Place your own `content.jpg` and `style.jpg` in the project folder before running the script.

## 🚀 How to Run

1. Install dependencies:
```bash
pip install tensorflow matplotlib numpy
```

2. Add `content.jpg` and `style.jpg` in the project folder.

3. Run the script:
```bash
python style_transfer.py
```

4. Output will be saved as `stylized-image.png`.

## 📚 Reference
Based on the paper: *A Neural Algorithm of Artistic Style* by Gatys et al.