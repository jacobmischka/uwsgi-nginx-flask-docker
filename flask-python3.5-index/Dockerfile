FROM jacobmischka/uwsgi-nginx-flask:flask-python3.5

MAINTAINER Jacob Mischka <jacob@mischka.me>

# Add app configuration to Nginx
COPY nginx.conf /etc/nginx/conf.d/

# Copy sample app
COPY ./app /app
