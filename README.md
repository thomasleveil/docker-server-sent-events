docker-server-sent-events
=========================

Docker image running the example code for [Server-Sent Events](http://flask.pocoo.org/docs/0.10/quickstart/) (SSE).


run
---

    docker run -d -p 80:80 tomdesinto/server-sent-events


build
-----

	docker build --force-rm -t server-sent-events github.com/thomasleveil/docker-server-sent-events

