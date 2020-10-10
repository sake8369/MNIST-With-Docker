# Using a Linux micro-container
FROM ubuntu:latest
From python:3.6

RUN apt-get upgrade
RUN apt-get update

RUN apt-get install -y \
    python \
    python-pip \
    ca-certificates

# Set up workspace
RUN mkdir /mnist

WORKDIR /mnist
ADD pytorch-mnist/requirements.txt /mnist
ADD pytorch-mnist/main.py /mnist

# Install Python libraries
RUN pip install -r requirements.txt


# Train and test the model
CMD ["python", "main.py"]

