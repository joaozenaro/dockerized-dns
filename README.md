# DNS Bind9 + Apache + Webmin

![Docker](img/docker.png)
Containers rodando

![Webmin](img/webmin.png)
Webmin rodando

### Para executar
```console
$ docker compose up -d
```

### Inspecionar o container `client` e requisitar `aula.net`
```console
$ docker exec -it client bash
/# curl aula.net
```

Por simplicidade, para acessar o webmin é necessario definir uma senha pra o usuario root
```console
$ docker exec -it server bash
/# passwd
```
