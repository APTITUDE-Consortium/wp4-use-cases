# Documentation builder

## Docker-based process

Build and start the builder container:
```
docker compose up

```

While the container runs, build the documentation with the following command:
```
docker exec -it doc_builder /D4.1/build.py html   # pdf, docx or leave empty for all
```

## Local installation

### Setup

1. Install [Quarto](https://quarto.org).

2. Set up the local Python environment:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Use

```
source .venv/bin/activate
python build.py
```
