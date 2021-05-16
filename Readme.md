# Odoo Deployment with Ansible

Deployment using Ansible to deploy components of odoo, postgresql and Traefik as Docker images.


![](odoo-traefik.png)
# Roles

## PostgresSQL

Role to install PostgreSQL

## Odoo

Role to install Odoo with link to Postgresql database

## Traefik

Role to install Traefik as reverse proxy using Letsencrypt for SSL certificate