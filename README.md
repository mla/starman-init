starman-init
============

RHEL/CENTOS init script for Starman web server in *production environments*

Applies all suggestions from the docs, including:
- Uses start_server superdaemon for graceful restarts
- Runs server as unprivileged user/group "nobody"
- Expects a local Perl install using plenv

Script requires customization for specific application and environment.
See also perldoc Starman and Server::Starter.

- [starman](http://search.cpan.org/dist/Starman/script/starman)
- [start_server](http://search.cpan.org/dist/Server-Starter/start_server)

Repository:
https://github.com/mla/starman-init
