# Installing Django on Docker

Installing a Django application on Docker, using docker-compose.

## Environment settings (3.9)

```
python3 -m env env
```

## Install and run Docker

Install and run Docker, then run the docker-compose file with the following command:

```
docker-compose up -d
```

## App and DB routes

```
web: localhost:8000/polls
db: localhost,5432
```

## Authors

- [@dj.pablo.ac](https://gitlab.com/dj.pablo.ac)


## License

[MIT](https://choosealicense.com/licenses/mit/)
