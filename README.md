# Cloudleton

This project contains several apps that we use and groups them together using docker-compose.
HAProxy supplies HTTPS support for all apps (serves as a reverse-proxy), and communicates with them through their dedicated shared docker bridge network.

Apps:
* HAProxy
* PyPi Server
* Devdocs
* WikiJS (with PostgresDB)
* Pushon
