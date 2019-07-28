FROM python:2-alpine AS backend

COPY backend-sample-app.py /usr/src/app/

WORKDIR /usr/src/app/

EXPOSE 9000

CMD ["python", "/usr/src/app/backend-sample-app.py"]
