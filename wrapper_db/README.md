Для инициализации необходимо вызвать New с параметрами

```go
db.New(viper.GetString("app.db.addr"),
			viper.GetString("app.db.user"),
			viper.GetString("app.db.password"),
			viper.GetString("app.db.port"),
			viper.GetString("app.db.name"))
```
