FROM nginxinc/nginx-unprivileged:1.25-alpine@sha256:1e29add3cbd3c5684200a9e2b1cc6a02f34285c3dbae20c4f242ff04099f9bbc

COPY ./nginx.conf ./ready_response.conf /etc/nginx/
COPY ./pre-stop.sh /
