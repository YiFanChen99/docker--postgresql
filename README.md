# docker--postgresql

## 運行

```
docker-compose up -d
```

## Test connecting after run (by psql)
```
psql -h localhost -p 5433 -U user -d db_name
> Password for user user: password
```

## 說明

* Using postgresql:11
* 會使用設定檔 `share/postgresql.conf`
