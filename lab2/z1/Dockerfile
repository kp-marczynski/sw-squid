FROM sameersbn/squid:3.5.27-2
RUN apt-get update && \
    apt-get install -y iputils-ping curl net-tools apache2-utils iproute2 wget && \
    htpasswd -bmc /etc/squid/passwd dev1 pass && \
    htpasswd -bm /etc/squid/passwd dev2 pass && \
    htpasswd -bm /etc/squid/passwd dev3 pass && \
    htpasswd -bm /etc/squid/passwd dev4 pass && \
    htpasswd -bm /etc/squid/passwd dev5 pass && \
    htpasswd -bm /etc/squid/passwd dev6 pass && \
    htpasswd -bm /etc/squid/passwd des1 pass && \
    htpasswd -bm /etc/squid/passwd des2 pass && \
    htpasswd -bm /etc/squid/passwd des3 pass && \
    chmod o+r /etc/squid/passwd
