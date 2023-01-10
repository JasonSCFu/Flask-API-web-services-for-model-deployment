
# <h1 align="center" id="heading">Flask for Deep Learning</h1>

## What is Flask? ##

Flask is a micro web framework written in Python. A micro web framework is a web development framework with an easy setup and can be used in developing minimalistic web applications. It was created to build web apps with the Python programming languange. It was designed to be easy, fast, and to scale up complex applications and microservices. Flask is very beginner-friendly because of its simplicity, giving developers room to learn and understand it better. It also enables developers to create apps effortlessly and quickly.



## Flask and Deep Learning Web Services ##

Suppose you would like to create websites based on neural networks. In that case, we must expose the neural network so that Python and other programming languages can efficiently execute. The usual means for such integration is a web service. One of the most popular libraries for doing this in Python is [Flask](https://palletsprojects.com/p/flask/). This library allows you to quickly deploy your Python applications, including TensorFlow, as web services.

Neural network deployment is a complex process. When large numbers of clients must access your model, scalability becomes essential. The cloud usually handles this. The designers of Flask did not design for high-volume systems. When deployed to production, you will wrap models in [Gunicorn](https://gunicorn.org/) or TensorFlow Serving. Everything presented in this part ith Flask is directly compatible with the higher volume Gunicorn system. When early in the development process, it is common to use Flask directly.


In the flask.ipynb, I will show how to 
* 1: create a simple "Hello world" Flask server.
* 2: create a Flask wrapper for neural network prediction.
* 3: create a Flask web service to classify images using MobileNet.