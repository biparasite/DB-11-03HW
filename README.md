# Домашнее задание к занятию " `ELK` " - `Сулименков Алексей`

---

## Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/\_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

### Ответ

![Elasticsearch](https://github.com/biparasite/DB-11-03HW/blob/main/Elasticsearch.png)

---

## Задание 2. Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /\_cluster/health?pretty.

### Ответ

![Kibana](https://github.com/biparasite/DB-11-03HW/blob/main/Kibana.png)

---

## Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Ответ

![Logstash](https://github.com/biparasite/DB-11-03HW/blob/main/Logstash.png)

---

## Задание 4. Filebeat

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

### Ответ

![Filebeat](https://github.com/biparasite/DB-11-03HW/blob/main/filebeat.png)

---
