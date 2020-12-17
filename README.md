# WP Stack

[![Docker Automated build](https://img.shields.io/docker/automated/tfirdaus/wp-stack.svg?style=flat)](https://hub.docker.com/r/tfirdaus/wp-stack/) [![Docker Pulls](https://img.shields.io/docker/pulls/tfirdaus/wp-stack.svg?style=flat)](https://hub.docker.com/r/tfirdaus/wp-stack/) [![Docker Build Status](https://img.shields.io/docker/build/tfirdaus/wp-stack.svg?style=flat)](https://hub.docker.com/r/tfirdaus/wp-stack/) [![Travis](https://img.shields.io/travis/tfirdaus/wp-stack.svg?style=flat)](https://travis-ci.org/tfirdaus/wp-stack) [![License](https://img.shields.io/github/license/tfirdaus/wp-stack.svg?style=flat)](https://github.com/tfirdaus/wp-stack)

> Docker images to run a WordPress localhost environment

The image extends the image from [WP Docklines](https://github.com/tfirdaus/wp-stack) and brings additional stacks that'll typically needed needed when working on a WordPress project, like a plugin or a theme, in a localhost environment with Docker. These images include:

- [PhpRedis](https://github.com/phpredis/phpredis) for a persistent Object Cache backend powered by [Redis](https://redis.io/).
- [XDebug](https://xdebug.org/) for advanced debugging and profiling. _(Coming Soon)_
- *Sendmail* to send outgoing emails. _(Coming Soon)_
