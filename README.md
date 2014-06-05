# Setup

```
heroku create -b https://github.com/kr/heroku-buildpack-go.git
git push heroku master
heroku scale bench=10PX
```
