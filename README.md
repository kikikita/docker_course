# Docker_course

## Мини-приложение Todo List.

- docker-compose up

############# Примеры некоторых команд #############

### Добавить запись в Todo List: 
#curl -X PUT localhost:8000/api -H 'Content-Type: application/json' -d '{"text":"Kill Bill","status":"active"}'

### Получить записи из Todo List:
#curl localhost:8000/api

### Зайти в базу данных для взаимодействия с данными:
# docker exec -it database psql --username docker_app --dbname docker_app_db
# Пример запроса: SELECT * FROM app_table;
