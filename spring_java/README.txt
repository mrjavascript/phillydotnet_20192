TO CREATE

https://start.spring.io/

TO RUN

gradle bootJar

docker build -t dockerdemo_spring .

docker run -p 5050:8080 dockerdemo_spring