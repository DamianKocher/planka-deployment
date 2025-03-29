FROM nginxinc/nginx-unprivileged:mainline-alpine-slim@sha256:2ff8b79ebe8a9bb403306866850faefe2ef9f447841767b25ba4d0b49518b541

USER root

COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

EXPOSE 443

USER nginx

CMD ["nginx", "-g", "daemon off;"]