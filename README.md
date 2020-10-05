# Neural_Style_Transfer

[![GitHub repo size](https://img.shields.io/github/repo-size/pcsingh/Neural_Style_Transfer?logo=github)](https://github.com/pcsingh/Neural_Style_Transfer/)

This is a Deep Learning model which will help you to transfer an style into your favourite image. I have used `VGG19` pre-trained model which consists of 16 convolution layers, 3 Fully connected layer, 5 MaxPool layers and 1 SoftMax layer. Below you can see the demo of the model.


![style image 1](images/style.jpg) &emsp;&emsp;&emsp;&emsp; <img src="images/content_2.jpg" width="200">

Output after 1000 iterations

![output image](images/output.png)

## How you can use

You can also use this model to train your own style and content images. I am supposing that you know about the [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb). First fork the repo from top right corner. Clone it using your cli tool. Go to the Google Colab or your local Jupyter Notebook and open `NST.ipynb` file.

Make small changes assign position of your style and content file to variables `style` and `content` in the second cell of notebook.
```python
style = 'your_style_image'
content = 'your_content_image'
```

Hurray! You are ready to see the output of the model.
