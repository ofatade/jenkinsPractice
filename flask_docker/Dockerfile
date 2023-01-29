FROM python3.11.1



COPY  requirements.txt /app/requirements.txt

WORKDIR /app

RUN pip install -r requirements.txt

COPY . ./app 

ENTRYPOINT ["python"]

CMD ["app.py"]