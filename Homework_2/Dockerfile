FROM python
RUN mkdir /flask
WORKDIR /flask
COPY ./index.html templates/
COPY ./app.py ./
EXPOSE 5000
RUN pip install flask
CMD ["python", "./app.py"] 