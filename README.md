# Malaria Detection Deep Learning App

## Project Overview:

The Malaria Detection Deep Learning App utilizes transfer learning with the VGG19 convolutional neural network architecture to provide accurate and efficient diagnosis of malaria from microscopic images.

## Key Components:

### 1. Dataset:

The Malaria Detection App utilizes [Malaria Cell Images Dataset from Kaggle](https://www.kaggle.com/datasets/imdevskp/malaria-dataset), comprising thousands of microscopic images of blood smears, labeled as infected or uninfected.


### 2. Transfer Learning with VGG19:

The VGG19 model, renowned for its depth and performance in image classification, is employed as a feature extractor. By fine-tuning the model's parameters on the malaria dataset, the app becomes adept at recognizing patterns indicative of infected and uninfected cells.

### 3. Flask Web Application:

To make the deep learning model accessible and user-friendly, the Malaria Detection App is integrated with a Flask web application. Users can upload microscopic images, and the app promptly provides predictions on whether the cells are infected with malaria or not.
## App Screenshot:

![Malaria Detection App](./screeshots/screenshot.png)




## Usage:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/youssafB/DL-Malaria-detection.git
   cd DL-Malaria-detection

2. **install Dependencies:**
  ```bash
   pip install -r requirements.txt

3. **Run the App:**
```bash
python app.py

4. **Upload an Image:**
 Click on the "Choose File" button to select a microscopic image.
 Click the "Upload" button.
 View Prediction:

The app will display the uploaded image along with the model's prediction.

## Future Enhancements:
As a continuous project, future enhancements may include:

Integration with mobile platforms for broader accessibility.
Improved model accuracy through additional fine-tuning and augmentation techniques.
Deployment on cloud platforms for scalable and efficient usage.

I
