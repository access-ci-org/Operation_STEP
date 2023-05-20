# This is the base image for the container
FROM alpine:3.9

# Installing python
RUN apk add --update py3-pip

#copying the file to the container 
COPY diceroll.py /usr/src/diceroll/

#Running the application
CMD ["python3", "/usr/src/diceroll/diceroll.py"]