# Handwritten_Equation_Solver_CNN
## About
A **CNN model** to predict and solve **Mathematical Handwritten Equations**. The data consists of around **10,000 images** of handwritten digits and symbols:
- [1,2,3,4,5,6,7,8,9,0]
- [ + , - , * ]

> Able to solve any equation consisting digits from 0-9 and symbols +, -, x . <br />
> Written equation should be in black on white background paper.

## Convolutional Neural Network
- Two Convolutional Layers
- Two MaxPooling Layers
- Dropout Layer
- Flatten Layer
- Two Dense Layers using Relu activation
- Output Layer using Softmax activation
- Adam optimizer for compilation

The architecture of the model is in file *model_plot.png*.<br />

<img src="https://i.ibb.co/JsyRqFJ/Capture1.png" width="600" height="300"><br />

```
Accuracy: 99.2%
```

## Tools
- TensorFlow / Keras
- OpenCV
- Pandas / Numpy
- Matplotlib

## Usage
To create a CSV file:
```
Extract Train Images.zip
```
```
Run Data_Extraction.ipynb
```
To train the model: <br />
*Either download Extracted.csv or create CSV file, then*
```
Run Train_CNN.ipynb
```
To test the model: <br />
*Either download already trained model_final.h5 & model_final.json or successfully train the model, then*
```
Run Test_CNN.ipynb
```
*A test image is provided in test_im.png.*

## Sample Test
<br />
<img src="https://i.ibb.co/s6Lnpb0/test-im.png" width="190" height="85">
Result:<br /> <br />
<img src="https://i.ibb.co/fxRFbHG/Capture3.png" width="150" height="50"><br />
