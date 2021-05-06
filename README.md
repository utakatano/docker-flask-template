# Flask Template with Docker/Docker Compose

Flask template working with Python3.
If you installed Docker/Docker Compose, you don't need to install Python and Flask in your local machine.

This flask source code is based on the [Quickstart](https://flask.palletsprojects.com/en/1.1.x/quickstart/). 

## Environment

- Python ... 3.10.0a7
- [Flask](https://flask.palletsprojects.com/) ... 1.1.2

## How to confirm in local

1. Build and up by docker-compose command and attach the docker container.
Or click left lower icon in VS code when you use VS code and installed Remote Containers in the extension.

```sh
% docker-compose up -d --build
% docker-compose exec app bash
```

2. Run below commands.

```sh
/app＃ export FLASK_APP=hello.py
/app＃ flask run --host=0.0.0.0
```

3. You can see the result in `http://localhost:8080` of your browser.