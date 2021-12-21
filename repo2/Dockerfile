FROM httpd
RUN rm -f /usr/local/apache2/htdocs/index.html
ADD ./index.html /usr/local/apache2/htdocs/
EXPOSE 80
ENTRYPOINT ["httpd-foreground"]

