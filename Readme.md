## PASSOS:

1. docker build -t gweisheimer/conversao-temperatura:v1 ./src
2. docker push gweisheimer/conversao-temperatura:v1
3. docker tag gweisheimer/conversao-temperatura:v1 gweisheimer/conversao-temperatura:latest
4. docker push gweisheimer/conversao-temperatura:latest
5. docker run -d --name conversao-temperatura -p 8080:8080 gweisheimer/conversao-temperatura:v1
