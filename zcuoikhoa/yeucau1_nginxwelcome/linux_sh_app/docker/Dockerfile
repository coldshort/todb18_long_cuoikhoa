FROM nginx:alpine

# envsubst nằm trong gettext
RUN apk add --no-cache gettext

WORKDIR /usr/share/nginx/html

# Template trang welcome
COPY index.template.html /usr/share/nginx/html/index.template.html
