FROM python:3.7
CMD ["flask", "run", "--host=0.0.0.0"]
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
