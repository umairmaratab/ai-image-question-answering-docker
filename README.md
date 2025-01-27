# AI image question answering app

A fully-integrated application that leverages the Transformer-based VILT model for image-based question answering.

- Model can be accessed via the `/ask` endpoint.

## Project Setup

- Make sure you have `python3` installed
- Create a virtual envionment, you can use `venv` to do that with `python3 -m venv <environment_name>`
- Clone the repository.
- Install the requirements via `pip install -r requirements.txt`
- Once the requirements successfully gets installed execute this to run the app: `fastapi dev app.py`
- After that go to `localhost:8000/docs`

#### Docker setup

If you want to run the app in the docker environment what you only need is `docker`

- In the project repository you can execute this: `sudo docker compose up --build`
