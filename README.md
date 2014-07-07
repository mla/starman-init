starman-init
============

RHEL/CENTOS init script for Starman web server in production environment

Applies all recommended best-practices from the docs, including:
- Uses start_server superdaemon for graceful restarts
- Runs server as unprivileged user/group "nobody"
- Expects a local Perl install using plenv

Script will need to be customized for your specific application/environment.
See also perldoc Starman and Server::Starter.

Repository:
https://github.com/mla/starman-init
