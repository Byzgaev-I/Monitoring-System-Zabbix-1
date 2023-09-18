# «Система мониторинга Zabbix» - Бызгаев Александр

### Задание 1

Установите Zabbix Server с веб-интерфейсом.

**Процесс выполнения**

1) Выполняя ДЗ, сверяйтесь с процессом отражённым в записи лекции.
2) Установите PostgreSQL. Для установки достаточна та версия, что есть в системном репозитороии Debian 11.
3) Пользуясь конфигуратором команд с официального сайта, составьте набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.
4) Выполните все необходимые команды для установки Zabbix Server и Zabbix Web Server.  

**Требования к результатам**  

Прикрепите в файл README.md скриншот авторизации в админке.  
Приложите в файл README.md текст использованных команд в GitHub.

 ***Решение***

 Zabbix server устанавливал в последовательности лекции Артура Сагутдинова, но с учетом 12 версии Debian (bookworm) 
 
![Image alt](https://github.com/Byzgaev-I/Monitoring-System-Zabbix-1/blob/main/Авторизация.png)

![Image alt](https://github.com/Byzgaev-I/Monitoring-System-Zabbix-1/blob/main/Авторизация%202.png)

GiyHub только овладеваю, так как домашки в других группах сдавал ссылками на гугл хранилище.
Пользуюсь GitKraken, GitHub Desktop ну и через терминал.

git add  
git commit -m "Readme.md"  
git push  
  
git status  
  
git add  
git commit -m "Update Readme"  
git push  

---

### Задание 2

Установите Zabbix Agent на два хоста.

***Процесс выполнения***

 1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
 2. Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
 3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
 4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
 5. Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов

 ***Решение***

Установил агент на две виртуальные машины.

![Image alt]([https://github.com/Byzgaev-I/Monitoring-System-Zabbix-1/blob/main/Агент%20на%202%20машины.png)


