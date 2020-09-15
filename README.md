# Titanic Predictions

Analysing Titanic dataset using Apache SparkML on a Docker container

## How to run

This command will pull the image from Docker Hub (if it is not already present on the local host):
```
docker pull edvlavr/titanic:0.0.1
```
Then this command will start a container running a Jupyter Notebook server and will expose the server on host port 8888:
```
docker run -p 8888:8888 edvlavr/titanic:0.0.1
```
Server logs and URLs will appear on container start. Copy and paste the last URL in your browser

### Results

##### Logistic Regression accuracy: 78.07%
##### Decision Tree accuracy: 85.09%
##### Random Forest accuracy: 84.21%

<a href="https://commons.wikimedia.org/wiki/File:RMS_Titanic_3.jpg#/media/File:RMS_Titanic_3.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1200px-RMS_Titanic_3.jpg" alt="RMS Titanic 3.jpg"></a>
