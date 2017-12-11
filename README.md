# wikimedia-docker
deploy wiki/mediawiki using docker and fig.

component including:
- mediawiki
- mysql


## deploy

~~~bash
$ sudo curl -L https://github.com/docker/compose/releases/download/1.17.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose ; sudo chmod +x /usr/local/bin/docker-compose
$ docker-compose -f fig.yml up
~~~
