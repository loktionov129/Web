FROM nginx:stable-alpine
COPY nginx.conf /etc/nginx/conf.d/default.conf

# support running as arbitrary user which belogs to the root group
RUN chmod g+rwx /var/cache/nginx /var/run /var/log/nginx
