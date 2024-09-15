FROM devopsedu/webapp:latest
COPY target/*.zar /var/www/html/
RUN cd /var/www/html/
RUN unzip *.zar
EXPOSE 89
CMD ["apache2-foreground"]
