# rails_docker_starter

This is a script to launch a new Rails 7 app in a Docker container. It's based on the article [on Docker's website](https://docs.docker.com/samples/rails/) with updates based on things that I ran into.

## Who is this for

This is for anyone who wants to start a new Rails 7 app quickly on MacOs

## How does it work?

Just clone it down and run it in your project directory similarly to how you would run `rails new`

```
➜  projects git clone git@github.com:radixhound/rails_docker_starter.git

rails_docker_starter/new_rails.sh my_project
```

This will create a new Rails 7 app in that folder with that name

## Prerequisites

In order to get this to work you'll need a bunch of things already going for you. I'm not sure exactly what they are at the moment but something like:

1. Command line tools (`xcode-select --install`)
2. Git installed (duh)
3. [Docker Desktop](https://docs.docker.com/desktop/install/mac-install/)

Let me know if I missed something.

## No Guarantees

Hey, I just put this together as I was setting this up for myself so that I could iterate and learn faster. I hope it helps, I'm unlikely to being doing a lot of maintenance on it.
