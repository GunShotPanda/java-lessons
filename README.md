pom.xml -- add as maven project

cd user-platform

mvn clean package -U
java -jar .\user-web\target\user-web-v1-SNAPSHOT-war-exec.jar

http://localhost:8080/