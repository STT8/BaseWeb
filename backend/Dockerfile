FROM docker.io/library/python:3.11-alpine

RUN addgroup -S appgroup && adduser -S appuser -G appgroup

WORKDIR /app

COPY --chown=appuser:appgroup app.py .

user appuser

EXPOSE 8080

CMD ["python", "app.py"]