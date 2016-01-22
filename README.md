# github2tele
Github webhook integrate with the Telegram

## Install requirements

```
$ pip install -r requirements.txt --upgrade
```

## Set environment variable and run

```
$ export PORT=8888      # Default is 8080
$ export TOKEN=<TOKEN>
$ export CHAT_ID=<Chat_id_you_want_notify>
$ python runserver.py
```

Get bot token : [https://core.telegram.org/bots](https://core.telegram.org/bots)

* Set webhook in Github. http://your.ip:port/gitlab/project

This is a simple test version that is not yet properly modified to receive Github webhook callbacks!
