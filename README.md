
# Music Genre Classifiction Using Deep Learning




## 📝 Description
Music is a universal language that has a
powerful impact on our emotions and experiences. This project aims to improve how we classify music into genres by using a technique called transfer learning. It will adapt a pre-trained model, VGG-16, which was originally used for identifying images, and fine-tune it with music data to achieve high accuracy in recognizing music genres.

## 🚀 Dataset
used the “GTZAN Dataset”. 

Link:  https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

This data set consists of 10 music genres with each genre containing about 100 audio .wav files.  

## 🎯Roadmap

-  **Preprocessing:**
   1. the audio data in the .wav format. The .wav file format uses a header that contains information about the audio data, such as the sample rate, bit depth, and number of channels .
   2. Using the Librosa python package to load each audio file and extract the signal from it. Command Used - _Librosa.load()_

  
- **Convert the signal to Mel Spectograms:**
  1. used the _librosa.feature.melspectrogram()_ function to convert the audio data to a Mel Spectrogram. This function takes two arguments such as the audio data  and the sampling rate of the audio. The function returns a numpy array representing the Mel Spectrogram. 

 
- **Model Implementation:**
   1.	The VGG-16 model was originally trained on the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) dataset.
   2.	The VGG-16 model was trained on the training set of the ImageNet dataset, which consists of images from 1000 different object categories.
   3.	Since dataset has 10 music genres, we changed the output layer of the model to fit our own dataset.
   4. Added a few more Dense layers and finally a SoftMax layer which outputs the probability for each class.



## Screenshots

![Mel Spectrogram](https://github.com/SanmeshSankhe/Music-Genre-Classification/blob/main/Mel%20Spectrogram.png)


## 🌟Tech Stack

Machine Learning, Python, PyTorch, sklearn, librosa, Pandas, matplotlib




## Support

For support, email Sankhesanmesh@gmail.com.


