FROM python:3.9
WORKDIR /testapp
ADD . /testapp
RUN pip install -r requirements.txt
ENV PORT=8080
ENV DEBUG=False
EXPOSE 8080
ENTRYPOINT python app.py
