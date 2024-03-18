This project is a simple Flask web application that provides an API endpoint for image classification.
It uses a pre-trained MobileNetV2 model from TensorFlow to predict the content of images.
The Flask application has the following endpoint:
/predict (POST): Accepts multipart/form-data with an image file under the key file. Returns a JSON object with the top 3 predicted labels and their corresponding probabilities.
The application was tested via Postman.
The screenshots showcase the image used for testing, POST request, logs and model prediction output.
