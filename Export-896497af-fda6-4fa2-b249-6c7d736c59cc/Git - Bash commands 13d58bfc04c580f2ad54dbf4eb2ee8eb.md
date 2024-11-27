# Git - Bash commands

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image.png)

это данные, по которым с вами могут связаться другие разработчики для обсуждения коммитов. То есть каждый ваш коммит будет подписан введённым ником и email-адресом.

Затем проверим

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%201.png)

# **Создание репозитория**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%202.png)

Оно означает, что Git начал отслеживать файлы проекта и будет записывать изменения в скрытую папку .git

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%203.png)

# Список базовых команд ориентации в папках

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%204.png)

Чтобы получить подробную документацию о какой-то команде — вызывайте справку.

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%205.png)

# Добавление Индекса, Коммит и Статус файла

## Индекс

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%206.png)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%207.png)

git add ****— промежуточная зона перед репозиторием.

## Статус - Файлы из Индекса

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%208.png)

Команда git status даёт представление о текущем состоянии репозитория. 

## Коммит

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%209.png)

**Short cut и исправление сообщения**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2010.png)

## Журнал коммитов

**Git log - весь список**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2011.png)

**Git show - просмотр одного коммита**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2012.png)

## Сравнение Репозитория и Коммитов

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2013.png)

# Возвращение к старым версиям

## Откат к последнему коммиту

**Кроме того можно возвращать изменения - ТОЛЬКО Файла**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2014.png)

**Кроме того можно возвращать изменения - ВСЕГО Коммита**

## Откат к любому коммиту

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2015.png)

Если мы вернулся на несколько коммитов назад, то в зависимости от опций (soft, mixed, hard) Git сохранит все последующие коммиты в Индексе/или нет. Это означает, что Git вероятно придётся делать **Merge** (слияние), то если изменения были на разных строчках, но Git просто объединит файлы, иначе он Внесёт изменения в файлы с пометками в Конфликтующих местах, где нужно выбрать нужные версии изменений 

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2016.png)

# Ветвление

## Создание ветки

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2017.png)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2018.png)

## Просмотр всех веток

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2019.png)

## Переключение между ветками

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2020.png)

**Short cut**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2021.png)

**Безопасная альтернатива**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2022.png)

## Merge (слияние)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2023.png)

## Удаление ветки

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2024.png)

# Подключение GitHub (удалённого репозитория)

## Привязка с GitHub

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2025.png)

## Просмотр всех подключённых Онлайн Репозиториев

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2026.png)

## Загрузка изменений на GitHub репозиторий

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2027.png)

Команда git push загружает изменения из локального репозитория в удалённый.

## Получение изменений из GitHub репозитория

## **Git pull**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2028.png)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2029.png)

**Git pull —rebase**

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2030.png)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2031.png)

## Если есть несохранённые изменения для git pull

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2032.png)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2033.png)

## Git Clone

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2034.png)

![image.png](Git%20-%20Bash%20commands%2013d58bfc04c580f2ad54dbf4eb2ee8eb/image%2035.png)