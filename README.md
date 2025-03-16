# Emotion-Recognition

This program uses FER2013 DATASET.

## About Dataset
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

I use only 3 categories (happy, neutral, suprise) aiming that I'll be creating other emotinal states using these 3 categories. But that will be a further issue.

You need to **download** the dataset with selected categories using this link: https://www.kaggle.com/datasets/msambare/fer2013

There should be test and train directories containg emotional states inside archive directory. 
<code> archive/test, train/happy, neutral, suprise </code>

After finising the setup open your source code with google colab and run the first shell. You need to select your data in here as zip file. Than keep running each shell.

After traning the model you can go strait into importing test files see the results!

Test model accuracy for improvments if you want and feel free to play around.

**Current Accuracy Score:**

<img src="https://github.com/user-attachments/assets/21c12c3b-79a2-45c3-99f0-f10d80f7bfb9" width="600">

