![enter image description here](https://github.com/prohetamine/docker-tor-request/blob/main/media/logo.png)

##### README доступен на языках: [Russian](https://github.com/prohetamine/docker-tor-request/blob/main/README/russian.md) | [English](https://github.com/prohetamine/docker-tor-request/blob/main/README.md)


# Docker Tor Request

> docker-tor-request - Мой первый докер контейнер 🐳.

### Почему ?
Мой опыт с докером ужасно мал, это значит что я должен учиться и идти с мачете через эти джунгли непонимания, это мой первый контейнер реализующий необходимую задачу запросов к серверу через Tor сеть каждый раз с новым ip.

### С чего начать

Установим контейнер из Docker Hub ```prohetamine/docker-tor-request```

```sh
$ docker pull prohetamine/docker-tor-request
```

Также сборка

```sh
$ git clone https://github.com/prohetamine/docker-tor-request.git
$ cd docker-tor-request
$ docker build . -t docker-tor-request
```

### Примеры и описание

Запуск контейнера и запрос к серверу. Также стоит помнить что контейнер для запросов использует _curl_ чтобы легче создавать конструкции изучите официальную [документацию](https://curl.se/docs/).

```sh
  docker run prohetamine/docker-tor-request -s https://api.ipify.org
```

### Контакты

Мой Телеграм: [@prohetamine](https://t.me/prohetamine), [канал](https://t.me/prohetamines)

Почта: prohetamine@gmail.com

Донат денег: [patreon](https://www.patreon.com/prohetamine)

Если у вас есть какие-либо вопросы и/или предложения, пожалуйста, напишите мне в телеграмме, если вы найдете ошибки также дайте мне знать, я буду очень благодарен.
