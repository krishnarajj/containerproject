FROM nginx
LABEL "PROJECT"="kv"
LABEL "AUTHOR"="KRISHNARAJ"
RUN apt update -y
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY ngin.conf /etc/nginx/conf.d/vproapp.conf
EXPOSE 80

