FROM python:3.13-slim
WORKDIR /app
COPY requirements.txt Boston_LR.pkl ./
RUN pip install -r ./requirements.txt

COPY app.py /app
ENTRYPOINT ["python", "app.py"]