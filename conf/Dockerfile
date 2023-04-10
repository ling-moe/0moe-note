FROM nginx
COPY . /html
RUN mv /html/conf/nginx.conf /etc/nginx/nginx.conf && rm -rf /html/conf && rm -rf /html/.github