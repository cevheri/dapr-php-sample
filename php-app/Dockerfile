FROM php:7-cli
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
CMD ["php", "-S", "0.0.0.0:8000", "app.php"]

# docker build -t cevheri/dapr-php-sample .
# docker push cevheri/dapr-php-sample:latest