# legacy-ruby-stack

This is designed to be a fully enclosed time-capsule of our old web applications stack. It is a research tool, an ocassional emergency migration pathway, but not really anything you should use unless you have a very good reason.

The stack is as follows.

* [Ruby Enterprise Edition](http://www.rubyenterpriseedition.com/) 1.8.7-2012.02
* [Phusion Passenger](https://www.phusionpassenger.com/) < 4
* Apache 2

## Getting started

You can get the latest image from [Docker Hub](https://registry.hub.docker.com/u/nytinteractive/legacy-ruby-stack/) and run an empty web server.

```bash
docker pull nytinteractive/legacy-ruby-stack
docker run -t nytinteractive/legacy-ruby-stack
```

By itself, it isn't very useful. Use it as a `FROM` image in a legacy application's [Dockerfile](https://docs.docker.com/reference/builder/).
