starman-init
============

RHEL/CENTOS init script for Starman web server in *production* environments

Applies all recommended best-practices from the docs, including:
- Uses start_server superdaemon for graceful restarts
- Runs server as unprivileged user/group "nobody"
- Expects a local Perl install using plenv

Script should be customized for specific application and environment.
See also perldoc Starman and Server::Starter.

Repository:
https://github.com/mla/starman-init
