FROM httpd:latest


WORKDIR /usr/local/apache2/htdocs
COPY index.html .
WORKDIR /usr/local/apache2/conf

RUN echo "Listen 9999" >> httpd.confc

EXPOSE 9999