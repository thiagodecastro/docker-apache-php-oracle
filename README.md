# docker-apache-php-oracle
Docker Image built on Debian, with Apache2, PHP5, OCI8 extension and Oracle Instant Client.

## Build the docker image :
    git clone https://github.com/thomasbisignani/docker-apache-php-oracle.git
    cd docker-apache-php-oracle
    docker build -t thomasbisignani/docker-apache-php-oracle .

## Or pull the image from Docker Hub :
    docker pull thomasbisignani/docker-apache-php-oracle

## Run the sample project :
    docker run -p 8080:80 -d -v $(pwd)/sample:/var/www/apache-php-oracle thomasbisignani/docker-apache-php-oracle

## Test your deployment :
* Open [http://127.0.0.1:8080](http://127.0.0.1:8080) in your browser
