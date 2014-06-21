starman-init
============

RHEL/CENTOS init script for Starman web server in production environments

Features/assumptions:
- Uses start_server superdaemon for graceful restarts
- Runs server as user/group "nobody"
- Expects a local Perl install using plenv

See also perldoc Starman and Server::Starter.

Repository:
https://github.com/mla/starman-init
