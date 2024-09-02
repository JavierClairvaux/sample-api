# How To Use

This is a sample APi that uses FastAPI. If you like to use this withouth docker you need install the dependencies on the `requirements.txt` files using PIP. Like so:

```console
pip install -r requirements.txt
```

Then run the code using:

```console
cd sample_api; fastapi dev ./main.py
```

However, you can run the code using Docker by building the image and then running the container:

Pull the container:
```console
docker pull ghcr.io/javierclairvaux/fast-api:latest
```

Run the container:
```console
docker run -p 3000:3000 ghcr.io/javierclairvaux/fast-api:latest 
```