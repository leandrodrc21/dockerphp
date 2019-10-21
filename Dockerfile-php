FROM php:7.2-apache
RUN apt-get update && apt-get install -y
RUN  apt-get -y install vim
RUN docker-php-ext-install mysqli pdo_mysql
RUN apt-get -y install git
RUN git clone git://github.com/leandrodrc21/phplogin.git
