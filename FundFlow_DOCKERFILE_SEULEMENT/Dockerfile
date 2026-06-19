FROM python:3.12-slim

ENV PYTHONDONTWRITEBYTECODE=1 \
    PYTHONUNBUFFERED=1 \
    PORT=8000 \
    DATA_DIR=/app/data

WORKDIR /app

COPY app.py /app/app.py
RUN mkdir -p /app/data

EXPOSE 8000

CMD ["python", "-u", "app.py"]
