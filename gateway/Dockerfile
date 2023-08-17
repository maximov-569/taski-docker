FROM nginx:1.22.1
COPY nginx_default.conf /etc/nginx/templates/default.conf.template

# If you aren't going to use custom nginx.conf, so just delete this string,
# otherwise place your custom conf next to the nginx_default.conf.
COPY nginx.conf /etc/nginx/nginx.conf
