### Запустите следующую команду
```sudo docker run nginx```
### Далее запустите
```sudo docker run -d -p 6666:80 --name=nginx_custom_html -v ${PWD}:/usr/share/nginx/html nginx```
### Готово, теперь вы заменили страницу nginx на свою
### И последнея команда для проверки
```curl localhost:6666/```