FROM openjdk:alpine

WORKDIR /calcjavadir/java

COPY . /calcjavadir/java 

RUN javac calc.java

CMD [ "java", "calc"]
