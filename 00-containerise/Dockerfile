FROM container-registry.oracle.com/java/jdk-no-fee-term:17-oraclelinux8

ARG JAR_FILE

EXPOSE 8080

COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java"]
CMD ["-jar","app.jar"]