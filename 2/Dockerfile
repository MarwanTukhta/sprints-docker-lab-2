FROM httpd:latest


WORKDIR /usr/local/apache2/htdocs
COPY index.html .
WORKDIR /usr/local/apache2/conf

# RUN echo "Listen 9999" >> httpd.conf or this:
RUN sed -i 's/Listen 80/Listen 9999/g' httpd.conf

EXPOSE 9999