FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip3 install django && \
    pip3 install mysql-connector-python


# Install required system packages
# RUN apt-get update \
#     && apt-get install -y python3-dev default-libmysqlclient-dev build-essential \
#     && apt-get clean \
#     && rm -rf /var/lib/apt/lists/*

# Install mysqlclient
# RUN pip3 install mysqlclient


#RUN pip install mysql-connector-python


# Set the working directory inside the container
WORKDIR /app

# Copy the entire application code into the container
COPY . /app/

# Expose the port your app runs on
#EXPOSE 80

# Command to run your application
#CMD ["python", "manage.py", "runserver", "0.0.0.0:80"]
