FROM python:3.8
LABEL maintainer="NamTe"
EXPOSE 3111
COPY ./techtrends /techtrends
WORKDIR /techtrends
RUN pip install -r requirements.txt
RUN python init_db.py
CMD ["python","app.py"]