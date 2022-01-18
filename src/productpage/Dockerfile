FROM python:3.8-bullseye

WORKDIR /app
COPY . /app

RUN pip install -r requirements.txt

EXPOSE 8082

CMD ["python","/app/productpage.py","8083"]