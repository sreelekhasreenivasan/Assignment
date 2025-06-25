FROM python:3.11-slim

WORKDIR /app

RUN pip install Flask==2.3.3

COPY . .

EXPOSE 8002

CMD ["python", "app.py"]