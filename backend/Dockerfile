FROM PYTHON:3.8:slim
WORKDIR /app
copy ./app
RUN pip install --no-cahe-dir-r requirements.txt
EXPOSE 5000
CMD [ "PYTHON","app.py" ]