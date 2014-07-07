starman-init
============

RHEL/CENTOS init script for Starman web server in *production* environments

Applies all recommendeds from the docs, including:
- Uses start_server superdaemon for graceful restarts
- Runs server as unprivileged user/group "nobody"
- Expects a local Perl install using plenv

Script requires customization for specific application and environment.
See also perldoc Starman and Server::Starter.

Repository:
https://github.com/mla/starman-init
