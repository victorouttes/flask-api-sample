# Run API (locally)

1) (Optional) Create/activate a virtual environment:

```
python -m venv venv
source venv/bin/activate
```

2) Install the requirements:

```
pip install -r requirements.txt
```

3) Run the command:

```
python app.py
```

# Dockerize

1) Create a docker image:

```
docker build -t my-flask-api-image:latest .
```

2) Create and run a container from image

```
docker run -d -p 5000:5000 my-flask-api-image:latest
```
