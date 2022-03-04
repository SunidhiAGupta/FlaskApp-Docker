# Step-1 Specify the base image
FROM python:3.10
# Step-2 Dwnload and install dependencies
RUN /bin/bash -c 'python -m pip install flask'
# specify the working directory/path
COPY ./app.py /app/
WORKDIR /app
# setup the start-up command
CMD python app.py
