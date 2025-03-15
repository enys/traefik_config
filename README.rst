Traefik Configuration
=====================
This is a template configuration setup for Traefik_ with a docker provider using docker-compose

.. _Traefik: https://traefik.io

Usage
=====
After creating your .env, using .env.example::

  $ docker-compose up

Basic Auth generation
=====================
htpasswd -nbB USER PWD

TODO
====

Cert resolvers
--------------
 Use dns challenge for ovh:
 https://www.alexandre-hublau.com/fr/posts/it/generer-certificat-https-docker-traefik/

 Use wildcard dns :
 https://docs.traefik.io/https/acme/#wildcard-domains

