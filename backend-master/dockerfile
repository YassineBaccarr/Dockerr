From adoptopenjdk:11-jre-hotspot
Volume /tmp
ADD targer/*.jar app.jar
CMD["java","-jar","app.jar", "--spring.profiles.active=prod"]
EXPOSE 8091
