## 1. Introduction

TensorFlow image with pyodbc == 4.0.30 and JRE

## 2. Requirements

1. [Docker](https://docs.docker.com/get-docker/)

## 3. Docker pull

You can download the full image from [Docker Hub](https://hub.docker.com/) with the following command.

````
docker pull davma/tensorflow-pyodbc-jre
````

## 4. Image build

You can run the image build with the following commands

````
git clone https://github.com/davma-io-images/tensorflow-pyodbc-java.git
cd tensorflow-pyodbc-java
docker build -t tensorflow-pyodbc-jre .
````

## 5.Documentation and guides

[TensorFlow](https://www.tensorflow.org/)

[docker TensorFlow](https://www.tensorflow.org/install/docker)

[Microsoft ODBC 17](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-2017)
