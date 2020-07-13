FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY /dist/tabslee /usr/share/nginx/html
COPY /nginx /etc/nginx/conf.d/
CMD ["nginx", "-g", "daemon off;"]
