# Docker Mysql and PhpMyAdmin

Thank you for the interest in Docker Mysql and PhpMyAdmin
This is the public Docker (docker-compose).

# How to use this image

Starting a MySQL instance is simple:

```console
$ docker-compose up
```

Access the application via:

```console
http://<host-ip>:8080/
```

Access the mysql via CLI:

```console
>docker exec -it <container-id> mysql -uroot -p
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)