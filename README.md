# demo-helm-microservice

Helmfile уже упакован в Docker-контейнер — ничего ставить на хост не нужно.

Для развёртывания микросервиса достаточно одной команды:

./helmfile sync

После успешного деплоя пропиши в /etc/hosts

127.0.0.1  frontend.local


Открой браузер и перейди на http://frontend.local — сайт будет доступен.
