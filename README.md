# vs-code-docker-python

A Python library for the Docker Engine API. It lets you do anything the docker command does, but from within Python apps – run containers, manage containers, manage Swarms, etc.

<h1>Installation</h1>
The latest stable version is available on PyPI. Either add docker to your requirements.txt file or install with pip:

<b>pip install docker</b>

Then we need the requirement.txt file to gather all of the requirement within the flask

<b>pip freeze > requirements.txt</b>

<h3>To Build The Image in Docker Run</h3> 

<b> docker build -t <image_name> . </b>

<h3>To run the python file in localhost run </h3>

<b>  docker run -d -p 8000:8000 --name <container_name> <image_name> </b>


Open a web browser and type the following address:

http://localhost:8000
