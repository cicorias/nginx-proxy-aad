FROM nginx:1.15

RUN apt update && apt upgrade -y

RUN apt install bash curl wget -y 
# certbot python-certbot-nginx -y

RUN wget https://dl.eff.org/certbot-auto \
     && chmod a+x ./certbot-auto

