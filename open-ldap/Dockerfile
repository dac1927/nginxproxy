FROM osixia/openldap:1.2.4 AS openldap
EXPOSE 389
EXPOSE 636
ENV LDAP_ORGANISATION "homelab"
ENV LDAP_DOMAIN="homelab.local"
ENV LDAP_ADMIN_PASSWORD="homelab!1"
CMD [ "--loglevel", "debug" ]