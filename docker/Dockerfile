#1.0.0
FROM python:3.9

WORKDIR /code

COPY ../requirements.txt /code/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt

COPY ../shortener_app /code/shortener_app

CMD ["uvicorn", "shortener_app.main:app", "--host", "0.0.0.0", "--port", "8000"]
