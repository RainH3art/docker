FROM openjdk
COPY . /java
WORKDIR /java
EXPOSE 80
RUN javac Main.java
CMD ["java", "Main"]