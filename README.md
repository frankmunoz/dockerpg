# dockerpg

Se debe ejecutar los siguientes comandos

```sh
$ docker build -t frankheavy/pg .
$ docker run -itd --restart=always --add-host="mydockerpg.com:127.0.0.1" frankheavy/pg
```

Y ya tenemos nuestro servidor postgres ejecutandose
