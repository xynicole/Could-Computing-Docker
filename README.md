# Could-Computing-HW2

## First Container
### URL for Docker image
https://hub.docker.com/r/xynicole/hw2part1

### Screenshot for the execution of docker container on GCP
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/P1GCP%20output.png)

### Screenshot for the command used to run your container on GCP
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/P1docker%20command.png)

###  [Dockerfile contents](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/Dockerfile)
```
FROM python:3
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN python3 hello.py
CMD ["python3", "hello.py"]
```

### [Source code file Python](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/hello.py)
```
def main():
    print("Hello World")


main()
```

## Second Container

### Screenshot for running Jupyter notebook
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/p2Jupyter%20output.png)

### Screenshot for the command 
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/P2command.png)

## Extra Credit
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/extra%20credit%20output.png)
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/extra%20credit%20outputv2.png)
![alt text](https://github.com/xynicole/Could-Computing-HW2/blob/main/Docker/extra%20credit%20.png)



