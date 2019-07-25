FROM python:3.6-slim
LABEL author="Mykola Shumakov"
COPY hits/app.py .
COPY requirements.txt .
RUN pip install -r requirements.txt
RUN mkdir -m777 logs
EXPOSE 5000 
ENTRYPOINT python app.py