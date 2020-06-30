FROM python
RUN apt-get update && apt-get install -y python3-pip
COPY . . 
RUN pip3 install flask 
RUN pip3 install flask-SQLAlchemy
RUN pip3 install pymysql
RUN pip3 install cryptography
EXPOSE 5000 
ENTRYPOINT ["/usr/local/bin/python3", "app.py"]
 

