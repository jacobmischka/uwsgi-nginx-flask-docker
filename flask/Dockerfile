FROM jacobmischka/uwsgi-nginx:python2.7

MAINTAINER Jacob Mischka <jacob@mischka.me>

RUN pip install flask

# Add app configuration to Nginx
COPY nginx.conf /etc/nginx/conf.d/

# Copy sample app
COPY ./app /app
