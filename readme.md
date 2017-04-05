Wobe App
========

Wobe demonstrates a simple service deployed on heroku using the experiemental docker service builds.

Install
-------

-	Have heroku setup on your system as describe in https://devcenter.heroku.com/articles/getting-started-with-go

Heroku
------

-	Run `make` and `make heroku` on the terminal

Now
---

-	Run `make` and `make now` on the terminal

-	Test App by sending the following through the terminal

```bash
curl -v localhost:4040/reverse -d '{"input": "bomba"}'
curl -v localhost:4040/reverse -d '{"input": "bomba"}'
```
