# Spacebar

Experimenting with [Django](https://www.djangoproject.com/) and [spacetraders.io](https://spacetraders.io/)


![Gundam Space Battles](https://media1.giphy.com/media/93QGXKq4uLEgo/200.gif)


### Setup notes

Installing `mysqlclient` on Apple Silicon 

```
brew install mysql-client pkg-config
```

```
export PKG_CONFIG_PATH="/opt/homebrew/opt/mysql-client/lib/pkgconfig"
poetry add mysqlclient
```