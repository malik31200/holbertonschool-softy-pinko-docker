FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y python3 python3-pip

RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

RUN pip3 install flask

# Definite the directory of work
WORKDIR /app

# Copy the python's file in the contnair
COPY ./api.py /app/api.py

# Run the flask application
# with "python3 api.py"
CMD ["python3", "api.py"]