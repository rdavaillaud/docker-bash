# docker-bash
Let you run a bash inside your docker.

## How do I install `docker-bash`?

Just put `docker-bash` into `/usr/local/bin`, like this:

    chmod +x docker-bash && sudo cp docker-bash /usr/local/bin

##  How do I *use* `docker-bash`?

You can enter your container with:

    docker-bash CONTAINER

And you will be on the root prompt

You can run a command inside your container with

    docker-bash CONTAINER 'my command'

