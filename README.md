starman-init
============

RHEL/CENTOS init script for Starman web server

Runs the Starman web server in production environment.

Features/assumptions:
- Uses start_server superdaemon for graceful restarts
- Runs server as user/group "nobody"
- Expects a local Perl install using plenv

See also perldoc Starman and Server::Starter.
