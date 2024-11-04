FROM python:3.6

LABEL version="1.0"
# Set a working directory in the container
WORKDIR /usr/src/app
# Install required packages
RUN pip install --no-cache-dir adjustText==1
# Copy your application files (if any) into the container
# COPY . .
# Define the default command to run when starting the container
CMD ["python"]
