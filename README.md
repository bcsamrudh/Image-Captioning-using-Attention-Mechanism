# Image-Captioning-using-Attention-Mechanism
It uses a encoder-decoder architecture to caption Images. I used a pretrained ResNet model as the encoder to extract image features, combined with an LSTM decoder implementing the Bahdanau attention mechanism to generate captions using the extracted features.

**Model Architecture**

![image](https://github.com/bcsamrudh/Image-Captioning-using-Attention-Mechanism/assets/114090255/069ab7ee-d611-4775-ba64-5b294d84c1c4)

**Dataset**

[Flickr 8K](https://www.kaggle.com/datasets/adityajn105/flickr8k) - It consists of a folder Images with images (.jpg format), and a a text file captions.txt. Each image has five captions each.
containing the captions corresponding to the image file names. 
<br>
<br>
The format of the text file is:
```
<image-filename>,<caption>\n
```



