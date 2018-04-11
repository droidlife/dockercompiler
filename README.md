# Docker Compiler
[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
> Online compiler API using docker

# Overview
This uses docker to compile untrusted code from the client and DRF is used to provide the high level api. 
<br>
Just a simple POST call with form data is enough to compile the code and get the output.

# Language Supported
1. Python (2.7) <br>
.... More are on the way

# Requirements
* Python (2.x, 3.x)
* Django (1.8+)
* Django REST (3.x)
* Docker

# Installation
 
1. Go to the root of the code directory where the Dockerfile is located and build the docker image by running <br>
  `docker build -t <image_name> .`
  
2. Open config.py and set these parameters: <br>
   * <i>DOCKER_IMAGE</i> :  The name of the docker image created
   * <i>LOCAL_DIR</i> : The path of the local directory needed to save the code.


  