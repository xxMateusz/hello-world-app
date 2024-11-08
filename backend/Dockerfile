
FROM python:3.9-alpine


RUN pip install flask


COPY app.py /app/app.py


WORKDIR /app


EXPOSE 5000


CMD ["python", "app.py"]

