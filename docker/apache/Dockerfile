# docker/apache/Dockerfile
FROM httpd:2.4.51

COPY my_project.apache.conf /usr/local/apache2/conf/my_project.apache.conf

RUN echo "Include /usr/local/apache2/conf/my_project.apache.conf" \
  >> /usr/local/apache2/conf/httpd.conf