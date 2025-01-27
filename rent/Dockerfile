FROM openjdk:21
COPY build/libs/carRentalEsiee-0.0.1-SNAPSHOT.jar .
CMD java -Xmx300m -Xms300m -XX:TieredStopAtLevel=1 -noverify -jar carRentalEsiee-0.0.1-SNAPSHOT.jar
EXPOSE 8080