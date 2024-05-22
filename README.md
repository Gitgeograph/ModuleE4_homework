##Проверить есть ли группа docker
```bash
groups
```
Если нет, добавить группу 
```bash
groupadd docker
```
Дать права
```
sudo usermod -aG docker $(whoami)
```

# Запуск:

```bash
gh repo clone Gitgeograph/moduleE4_homework
```

```bash
cd moduleE4_homework/djangodock
```
```bash
docker compose up
```

## images:
https://hub.docker.com/r/docgeograph/homework_nginx/tags

https://hub.docker.com/r/docgeograph/homework_django/tags

### admin:
login: admin

password: admin

