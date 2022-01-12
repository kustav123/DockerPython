FROM python:3.11.0a3-alpine3.15
RUN mkdir /app
ADD . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python", "staticOutput.py"]