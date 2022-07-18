# ati2-lab

## Getting Started

First, clone this repo recursively:

```bash
git clone --recursive https://github.com/Vixx-X/ati2-lab.git
```

Make sure you have installed docker-compose ([See how](https://docs.docker.com/compose/install/)).

Make sure there is no other service running on port 3000 or 8000.

## Run docker-compose

To run the project, you will need to do this command:

```bash
docker-compose up -d
```

And then, when it all finished, you should be able to open up the project on this urls:

Front : [http://localhost:3000](http://localhost:3000)
Back : [http://localhost:8000](http://localhost:8000)

## Remove project

```bash
docker-compose down
```

