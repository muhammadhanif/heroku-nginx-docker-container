# heroku-nginx-docker-container
Deploy nginx docker container to heroku

### How to deploy

```bash
git clone https://github.com/muhammadhanif/heroku-nginx-docker-container.git
```

```bash
cd heroku-nginx-docker-container
```

```bash
heroku login
```

```bash
heroku container:login
```

Change `APP_NAME` with the name of your heroku app.

```bash
heroku container:push web -a APP_NAME
```

```bash
heroku container:release web -a APP_NAME
```
