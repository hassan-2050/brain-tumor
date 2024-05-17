# Brain Tumor Classification app

This is my major project, which attempts to solve a medical challenge of tumor detection achieving a high-accuracy using transfer learning from a pre-trained model. This app uses a EfficientNetB0 pretrained model to classify images.

## Kaggle notebook
The kaggle notebook for the same is https://www.kaggle.com/code/architjee/brain-tumor-classification-from-mri

The kaggle notbook also contains step-by-step process of training and using and finally testing the model.

Then I used the trianed model, exported and converted it into a streamlit web-app, currently hosted at https://share.streamlit.io/architjee/braintumorclassifier/main.py


## About the application
This app takes an image ( Brain MRI ) input and classifies it into one of the following 4 categories:
1. No Tumor
2. Meningioma Tumor
3. Glioma Tumor
4. Pituitary Tumor


## Screenshot

> <img width="766" alt="Screenshot 2023-01-12 at 10 26 10 AM" src="https://user-images.githubusercontent.com/32292295/211980187-83bb531a-6887-4444-b81c-2cb6d68b3843.png">



## Installation
To run the application type in the terminal/powershell 
```bash
pip3 install -r requirements.txt
```

## Usage
Followed by 
```bash
streamlit run main.py
```

## Hosted at
Also hosted at https://share.streamlit.io/architjee/braintumorclassifier/main.py
Probably would have to turn off your adblocker to use it.

