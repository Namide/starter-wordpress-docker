# Docker with Wordpress

> Serve a Wordpress website with Docker


## Install

Install [Docker](https://docs.docker.com/install/) and run it.


**1. Run the command**

```bash
docker-compose up
```

**2. Open the links**
- [website](http://localhost:8080/) (Wordpress)
- [phpMyAdmin](http://localhost:8081/) (data base)


**3. Stop the server manually**

> The process will be stopped when the terminal will closed. But if you need to stop the server manually, follow this instructions.

_From the project directory (beside docker-compose.yml)_, run the command:
```bash
docker-compose down
```


## Directories & files

- `/docker-compose.yml` Docker config
- `/www` All the Wordpress files (generated)
- `/mysql-cache` Database persistent data (generated)
