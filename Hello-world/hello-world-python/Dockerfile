FROM python:alpine3.10 #base image
WORKDIR /app 
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 5000 #exposing the port 5000
CMD python ./launch.py #code where it print "hellowrold" --source code

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]