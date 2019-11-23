FROM sameersbn/squid:3.5.27-2
RUN apt-get update && \
    apt-get install -y iputils-ping curl net-tools apache2-utils iproute2 && \
    htpasswd -bmc /etc/squid/passwd user pass && \
    chmod o+r /etc/squid/passwd
