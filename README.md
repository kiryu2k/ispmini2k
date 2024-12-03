# ispmini

Минимальны набор контейнеров для запуска платформы с админкой

Один раз выполнить
```
docker login nexus.txix.ru
```

Поднять кластер
```
docker compose up -d
```

Выставить права на каталог `isp-config-service`
```
sudo chmod -R 777 ./isp-config-serivce
```

Перезапустить контейнеры (существует вероятность, что из-за неверно заданных прав, он могли не стартовать)
```
docker compose start
```

Админка и прокси для АПИ доступны тут
```
http://localhost:8001
```

X-application-token админки
```
74f3bc21-3dac-4532-9674-be4453732013
```

Для обновления
```bash
docker compose down
docker compose pull
docker compose up -d
```
