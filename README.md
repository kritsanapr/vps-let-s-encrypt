# Configuration VPS and Let's Encrypt with Docker Container

### What is SSL?

SSL is a standard security technology for establishing an encrypted link between a web server and a browser. This link ensures that all data passed between the web server and browsers remain private and integral.

### What is Let's Encrypt?

Let's Encrypt is a free, automated, and open certificate authority brought to you by the non-profit Internet Security Research Group (ISRG). It is intended to make it more secure and reliable to browse the web. Let's Encrypt is a service provided by the non-profit Internet Security Research Group (ISRG). Let's Encrypt is a Certificate Authority that provides an easy way to obtain and install free TLS/SSL certificates, thereby enabling encrypted HTTPS on web servers.

Command for start container

run command for create network webproxy

> docker create network webproxy

Start the container in background

> docker-compose up -d

Show all images

> docker images

Show the container

> docker compose ps
