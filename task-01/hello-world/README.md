# Building a Hello World API

## Create a Virtual Environment

```bash
python3 -m venv env
source env/bin/activate
deactivate #(to deactivate the virtual environment)
```

## Create a `requirements.txt` file

```bash
touch requirements.txt
```

### Add following packages in `requirements.txt`

```
fastapi[all]
```

### Install

```bash
pip3 install -r requirements.txt
```

## Run `Hello World`

- Make sure you are in the same directory as your `Hello World` script
- Run:

```bash
uvicorn main:app --reload
```

- [Link](http://127.0.0.1:8000/)
- [Docs - Swagger](http://127.0.0.1:8000/docs)
- [Docs - Redoc](http://127.0.0.1:8000/redoc)
- [Open API Schema](http://127.0.0.1:8000/openapi.json)
