
# Land Use Classification Prediction Visualizer in Flask App



## Local Installation

It's easy to install and run it on your computer.

```shell
# 1. First, clone the repo
$ git clone https://github.com/KevinmKrieg/satellite-image-classification/edit/main/flask_webapp
$ cd flask_webapp

# 2. Install Python packages
$ pip install -r requirements.txt

# 3. Run!
$ python app.py
```

Open http://localhost:5000

## Run with Docker

With **[Docker](https://www.docker.com)**, you can quickly build and run the entire application in minutes :whale:

```shell
# 1. First, clone the repo
$ git clone https://github.com/KevinmKrieg/satellite-image-classification/edit/main/flask_webapp
$ cd flask_webapp

# 2. Build Docker image
$ docker build -t keras_flask_app .

# 3. Run!
$ docker run -it --rm -p 5000:5000 keras_flask_app
```

Open http://localhost:5000 and wait till the webpage is loaded.

![App Gif](https://j.gifs.com/w0rxMX.gif)
