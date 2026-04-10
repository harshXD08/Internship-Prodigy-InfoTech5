# Internship-Prodigy-InfoTech5

#  Neural Style Transfer using PyTorch

##  Overview

This project implements **Neural Style Transfer**, a deep learning technique that combines the **content of one image** with the **style of another image** to generate a new artistic image.

Using a pretrained **VGG19 Convolutional Neural Network**, the model extracts content and style features and blends them through optimization.

---

##  Features

* Apply artistic styles to any image
* Uses pretrained VGG19 model
* Implements Gram Matrix for style representation
* Fully built using PyTorch
* Customizable content and style images

---

##  How It Works

1. Load content and style images
2. Pass both images through VGG19 network
3. Extract:

   * Content features (structure of image)
   * Style features (textures and patterns)
4. Compute:

   * Content Loss
   * Style Loss (using Gram Matrix)
5. Optimize a target image using gradient descent
6. Generate stylized output

---

##  Tech Stack

* Python
* PyTorch
* Torchvision
* PIL (Python Imaging Library)
* Matplotlib

---

##  Project Structure

```
neural-style-transfer/
│
├── notebook.ipynb        # Main implementation
├── content.jpg          # Input content image
├── style.jpg            # Style reference image
├── output.jpg           # Generated stylized image
└── README.md
```

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/neural-style-transfer.git
cd neural-style-transfer
```

### 2. Install dependencies

```bash
pip install torch torchvision matplotlib pillow
```

### 3. Run the notebook

Open `notebook.ipynb` and execute all cells.

---

##  Results

| Content Image | Style Image | Output Image    |
| ------------- | ----------- | --------------- |
| Your Image    | Style Art   | Stylized Output |

*(Add your actual images here for better presentation)*

---

##  Applications

* Digital art generation
* Image editing tools
* Creative AI applications
* Photo stylization

---

##  Future Improvements

* Add Streamlit web app interface
* Support multiple styles
* Improve performance with faster models
* Add real-time style transfer

