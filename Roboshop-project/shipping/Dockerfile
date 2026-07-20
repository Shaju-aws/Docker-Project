FROM maven:3.9.16
WORKDIR /app
RUN mvn clean package
COPY target/shipping-1.0.jar shipping.jar 
CMD ["java", "-jar" "shipping.jar"]