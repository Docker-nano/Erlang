Nano Erlang
===========

[![Build status][Build image]][Build]

This is the [Docker Nano](https://github.com/Docker-nano) image for Erlang v17.3.

* Docker Hub image: [`nano/erlang`][Docker Hub repo]
* Size: ~41MB

Usage
-----

Try one of the following.

* Run `docker run -it nano/erlang:latest` – launch interactive command prompt.
* Run `docker run -it --rm nano/erlang:latest erl -noshell -eval 'io:fwrite("Hello, World!\n"), init:stop().'`.
* Add `FROM nano/erlang:latest` to your Dockerfile.

  [Build]: http://travis-ci.org/Docker-nano/Erlang
  [Build image]: http://img.shields.io/travis/Docker-nano/Erlang.svg "Build status"
  [Docker Hub repo]: https://registry.hub.docker.com/u/nano/erlang/
