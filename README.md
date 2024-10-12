# ДЗ: Настраиваем split-dns
## Описание домашнего задания
1. взять стенд https://github.com/erlong15/vagrant-bind 
  - добавить еще один сервер client2
  - завести в зоне dns.lab имена:
    - web1 - смотрит на клиент1
    - web2  смотрит на клиент2
  - завести еще одну зону newdns.lab
  - завести в ней запись
    - www - смотрит на обоих клиентов

2. настроить split-dns
  - клиент1 - видит обе зоны, но в зоне dns.lab только web1
  - клиент2 видит только dns.lab
Формат сдачи ДЗ - vagrant + ansible
