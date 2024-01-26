FROM python:3.7-alpine
WORKDIR /app
ENV FLASK_APP=app.py
RUN pip install flask==2.2.5
EXPOSE 5000
COPY . .
RUN python app.py