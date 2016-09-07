# Lista de grupos técnicos do Telegram

A ideia dessa página é reunir todos os grupos técnicos que existem no Telegram.

## Reproduzindo esse site na sua estação com docker

Primeiro baixe todo esse código:

```
git clone git@github.com:listatelegram/listatelegram.github.io.git
```

Depois acesse a pasta listatelegram

Caso esteja usando MacOS, execute o seguinte comando:

```
docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll   -it -p $(docker-machine ip `docker-machine active`):4000:4000 jekyll/jekyll
```

Caso esteja usando GNU/Linux, execute o seguinte comando:

```
docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll
```
