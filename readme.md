# Docker with Wordpress

> Serve a Wordpress website with Docker


## Install

Install [Docker](https://docs.docker.com/install/) and run it.


**1. Run the command**

```bash
docker-compose up
```

**2. Open the links**
- [Wordpress](http://localhost:8080/)
- [phpMyAdmin](http://localhost:8081/)


**3. Stop the server manually**

_The process will be stopped when the terminal will closed. But if you need to stop the server manually:_

Go il the project directory (beside docker-compose.yml) and run the command:
```bash
docker-compose down
```


## Directories & files

- `/docker-compose.yml` Docker config
- `/www` All the Wordpress files (generated)
- `/mysql-cache` Database persistent data (generated)
