#Note: a very simple example

#Download base image for fun
FROM python:2.7-slim

#set the working dir
WORKDIR /app

#Copy the current directory to ontainer at /app
COPY . /app

#install something needed and also specified
RUN pip install --trusted-host pypi.python.org -r requirements.txt

EXPOSE 80

## Define ENV variable
ENV NAME World

## run app.py when launch
CMD ["python","app.py"]



