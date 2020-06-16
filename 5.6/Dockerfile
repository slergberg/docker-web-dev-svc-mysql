# Base image
FROM mysql:5.6.48

# Expose ports
EXPOSE 3306

# Healthcheck
ADD ./docker-healthcheck.sh /usr/local/bin/docker-healthcheck
RUN chmod +x /usr/local/bin/docker-healthcheck
HEALTHCHECK CMD docker-healthcheck
