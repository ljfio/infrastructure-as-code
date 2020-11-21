# note: never use the :latest tag in a production site
FROM caddy:2.1.1-alpine

COPY Caddyfile /etc/caddy/Caddyfile

ENTRYPOINT caddy run --config /etc/caddy/Caddyfile
