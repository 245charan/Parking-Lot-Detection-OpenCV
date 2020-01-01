# Deep_Learning
My projects and works in Deep Learning.

# 1. Sign Langauge Detection

  `Sign_Language.ipynb` is a jupyter notebook created on colab to recognize sign language digits from 0 to 9 from pictures with hand       signs. 

   We implement the CNN model using Keras.

   ## We have achieved 98.6% training accuracy.

   The Data Set is taken from https://www.kaggle.com/ardamavi/sign-language-digits-dataset. Visit the site for more information regarding the data.

   Incase any trobule in accessing the notebook, download and access it 
   Or access it on collab by clicking [here](https://colab.research.google.com/drive/1-8vVmqbrRRtrPwDw1l1AnhXhoiJ4TGLo)

# 2. Parking Lot Detection
 
  [![Watch the video](https://img.youtube.com/vi/Jf88JUq6ZSQ/maxresdefault.jpg)](https://youtu.be/Jf88JUq6ZSQ)
   
  https://youtu.be/Jf88JUq6ZSQ
  
## Prerequisites
    a. Python 3.7   
    b. OpenCV

## --------- Steps To Execute ------------

1. Open File Parking Lot Detection
2. Execute the main.py by command python main.py
3. Parking image will be shown
4. Mark the contours by clicking 4 corners for each spot they want tracked
5. Presses ‘q’ when all desired spots are marked.


  Video begins with the contours of Parking Slots overlayed the video.
  Occupied spots initialized with red boxes, available spots with green.
  Car leaves a space, the red box turns green.
  Car drives into a free space, the green box turns red.
