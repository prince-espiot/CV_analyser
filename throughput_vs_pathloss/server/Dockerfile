FROM python:3.10
WORKDIR /usr/src/app
COPY ./requirements.txt .
RUN pip install -r requirements.txt
COPY . .
EXPOSE 5005
CMD ["python3", "app.py"]