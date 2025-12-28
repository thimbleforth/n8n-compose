# n8n-compose

A basic n8n `docker-compose` setup.

Requires local certs to be generated and used, in its' current configuration.

Review the [tls.yml](./traefik/tls.yml) file to learn more.

If you don't know how to generate local HTTPS certificates and trust them in your browser, take a look at my  [OpenSSL Local CA notebook](https://github.com/thimbleforth/notebooks/blob/main/openssl-local-ca.ipynb) in my [Notebooks repo](https://github.com/thimbleforth/notebooks). It'll walk you through every step of creating your own local certificates.
