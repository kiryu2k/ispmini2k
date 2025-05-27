# ispmini

Минимальны набор контейнеров для запуска платформы с панелью администратора

Поднять кластер
```
docker compose up -d
```

Выставить права на каталог `isp-config-service`
```
sudo chmod -R 777 ./isp-config-serivce
```

Перезапустить контейнеры
```
docker compose restart
```

Панель администратора и прокси для АПИ доступны тут
```
http://localhost:8001
```

X-APPLICATION-TOKEN
```
74f3bc21-3dac-4532-9674-be4453732013
```

Для обновления
```bash
docker compose down
docker compose pull
docker compose up -d
```
