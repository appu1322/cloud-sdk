# Setup Cloud

## clone Submodules

To clone submodule, run:

```bash
git submodule init
```

```bash
git submodule update
```

## Installation and Run

To install the dependencies and run the containers, run:

```bash
docker-compose -f docker-compose.yaml --env-file .env up --build -d
```

## Stop running application

To stop all he running containers, run:

```bash
docker-compose -f docker-compose.yaml --env-file .env down
```


