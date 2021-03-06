# Quiver

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Sid200026/Quiver) [![Issues](https://img.shields.io/github/issues/Sid200026/Quiver)](https://github.com/Sid200026/Quiver/issues) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) ![Travis (.com)](https://img.shields.io/travis/com/Sid200026/Quiver)

## A social media website made using Django

A social media site which contains all basic features which Facebook and Instagram have to offer like Posts, Likes, Comments, Friend Request System and a Chat Application using Websockets protocol.

### Prerequisite

The chat application uses Redis as its backing store. To install Redis

For Mac,
```console
foo@bar:~$ brew install redis
```

For Linux : https://www.digitalocean.com/community/tutorials/how-to-install-and-use-redis

For Windows : https://redis.io/download

For Docker : https://hub.docker.com/_/redis/

Starting Redis

```console
foo@bar:~$ redis-server
```

### Installing

```console
foo@bar:~$ pip3 install -r requirements-dev.txt
foo@bar:~$ cd Quiver
```

##### Make Django aware of the models

```console
foo@bar:~$ python3 manage.py makemigrations
foo@bar:~$ python3 manage.py migrate
```

### To run the app

```console
foo@bar:~$ python3 manage.py runserver
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Siddharth Singha Roy** - *Initial work on Backend* - [Sid200026](https://github.com/Sid200026)
* **Rajlaxmi Roy** - *Initial work on Frontend* - [rosy2000](https://github.com/rosy2000)

See also the list of [contributors](https://github.com/Sid200026/Quiver/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
