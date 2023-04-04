FROM wordpress

COPY . /var/www/html

ENV WORDPRESS_DB_HOST=db
ENV WORDPRESS_DB_USER=wpdb_user
ENV WORDPRESS_DB_PASSWORD=wpdb_password
ENV WORDPRESS_DB_NAME=wordpressdb

CMD ["apachectl", "-D", "FOREGROUND"]

WORKDIR /var/www/html
