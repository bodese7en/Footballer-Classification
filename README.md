![image_2023-04-13_143026035](https://user-images.githubusercontent.com/115225579/231774231-50419f98-f801-42aa-aa63-34f2e97b6e0f.png)

# Footballer-Classification
This project is a full-stack machine learning web application that classifies images of footballers using scikit-learn libraries. The application is built using Python, HTML, CSS, and JavaScript. It uses a pre-trained machine learning model to classify images of footballers into three categories: Cristiano Ronaldo, Lionel Messi, and Neymar Jr.
The project consists of the following components:

## Flask API
The Flask API is the backbone of the project. It serves as the interface between the machine learning model and the web application. It provides the endpoints that receive image data, preprocess it, and pass it to the machine learning model for classification. The API then returns the predicted class and probability scores to the web application.

## Sci-kit Learn
The scikit-learn model was trained on a dataset of football player images using various machine-learning algorithms such as logistic regression, k-nearest neighbors, and decision trees. The best-performing algorithm was then selected and used to create the final model.

## Web Application
The web application is the front end of the project. It allows users to upload images of footballers and receive predictions on which footballer is in the image. The web application is built using HTML, CSS, and JavaScript, and is served using the Flask API. It uses the Dropzone.js library for image uploading and displays the predicted class and probability scores using a table.

## Getting Started
To run this project locally, you'll need to have Python installed on your machine. Clone the project repository, then navigate to the project directory and install the required Python packages using pip install. 
Once the packages are installed, you can start the Flask API by running the following command:
Copy code
python app.py 
This will start the Flask API on localhost:5000. You can then access the web application by opening index.html in your web browser.

## Installation
1.	Clone the repository: git clone https://github.com/bodese7en/footballer-classifier.git
2.	Install the required Python packages: pip install -r requirements.txt
3.	Start the Flask server: python app.py
4.	Open the web application in your browser: http://localhost:5000

## Usage
1.	Choose an image of a footballer to classify by clicking the "Choose File" button or dragging and dropping an image onto the designated area.
2.	Click the "Classify" button to classify the image.
3.	The web application will display the most likely footballer, along with a probability score.

## Dataset
The dataset used to train the model is a collection of images of Cristiano Ronaldo, Lionel Messi, and Neymar Jr.
Model
The machine learning model was trained using scikit-learn, a popular Python library for machine learning. The model uses a Support Vector Machine (SVM) algorithm to classify images of footballers.
Web Application
The web application was built using HTML, CSS, and JavaScript, with the Flask web framework used to handle server-side operations. The Dropzone.js library was used to handle image uploads and display uploaded images.

## Conclusion
This project demonstrates the power of machine learning in image classification and showcases how a machine learning model can be integrated into a web application. It also highlights the importance of using a full stack approach when building machine learning applications, and how Python, HTML, CSS, and JavaScript can be used together to build powerful applications.


