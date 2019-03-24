
FROM php:7.2-cli
COPY . /usr/src/myapp
ADD . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN apt-get update && apt-get install -y
CMD [ "php", "./script.php" ]