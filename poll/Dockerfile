FROM python:alpine3.13

EXPOSE 80
ENV PORT=80

COPY . /poll
WORKDIR /poll

RUN pip3 install -r requirements.txt

CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]
