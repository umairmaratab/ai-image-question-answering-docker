# AI image question answering app

A fully-integrated application that leverages the Transformer-based VILT model for image-based question answering.

- Model can be accessed via the `/ask` endpoint.

## Project Setup

#### Dev setup
- Make sure you have `python3` installed
- Create a virtual envionment, you can use `venv` to do that with `python3 -m venv <environment_name>`
- Clone the repository.
- Install the requirements via `pip install -r requirements.txt`
- Once the requirements successfully gets installed execute this to run the app: `fastapi dev app.py`

#### Docker setup

If you want to run the app in the docker environment what you only need is `docker`

- In the project repository you can execute this: `sudo docker compose up --build`

## Docs and Testing
- Once the setup is finished and app is up and running go to `localhost:8000/docs` to interact with the api (access model)
- To see the openapi docs go to `localhost:8000/redoc`

## Testing
- You can use `localhost:8000/docs` for testing or `Postman` if you are comfortable with that or any other tool.

**When the server is running in docker:**
![docker_app](https://github.com/umairmaratab/ai-image-question-answering-docker/blob/main/extras/doc_images/git-terminal.png)

**This is how API docs will look like:**
![api docs](https://github.com/umairmaratab/ai-image-question-answering-docker/blob/main/extras/doc_images/docs_image.png)

