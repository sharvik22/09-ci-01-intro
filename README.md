# Домашнее задание к занятию 7 «Жизненный цикл ПО» Шарапат Виктор

## Подготовка к выполнению

1. Получить бесплатную версию Jira - https://www.atlassian.com/ru/software/jira/work-management/free (скопируйте ссылку в адресную строку). Вы можете воспользоваться любым(в том числе бесплатным vpn сервисом) если сайт у вас недоступен. Кроме того вы можете скачать [docker образ](https://hub.docker.com/r/atlassian/jira-software/#) и запустить на своем хосте self-managed версию jira.
2. Настроить её для своей команды разработки.
3. Создать доски Kanban и Scrum.
4. [Дополнительные инструкции от разработчика Jira](https://support.atlassian.com/jira-cloud-administration/docs/import-and-export-issue-workflows/).

## Основная часть

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.

Остальные задачи должны проходить по упрощённому workflow:

1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.

**Что нужно сделать**

1. Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done. 
1. Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done. 
1. При проведении обеих задач по статусам используйте kanban. 
1. Верните задачи в статус Open.
1. Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.
2. Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания.

---

### Как оформить решение задания

Выполненное домашнее задание пришлите в виде ссылки на .md-файл в вашем репозитории.

---

### Решение

**Подготовка к выполнению**

![image](https://github.com/user-attachments/assets/40eb3f6f-4b22-4775-a075-3c194e50ed6b)

![image](https://github.com/user-attachments/assets/b02a479f-5696-42d0-b6e6-36821cdfda18)


**Что нужно сделать**

Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done.

![image](https://github.com/user-attachments/assets/68e8c49d-d336-4ca6-bad9-1747117e2ee4)

![image](https://github.com/user-attachments/assets/f227faeb-6cc0-4df3-8d4f-a3f8490bba47)


![image](https://github.com/user-attachments/assets/bc4d6cac-ea7c-44b1-a973-68f059fee596)

![image](https://github.com/user-attachments/assets/bb316faf-360c-469d-b15e-e7c82282d845)


![image](https://github.com/user-attachments/assets/a57e78e8-b89d-4620-a877-9669a0c8c11b)


**Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done.**
**В моей версии jira, поднятой с помощью docker, почему-то заблокированно Создайте задачу с типом epic.**

![image](https://github.com/user-attachments/assets/300b87ac-ed86-44de-a204-e415dcdf6755)

![image](https://github.com/user-attachments/assets/d72d57b1-151a-4475-85f2-e9bfec879fd6)


**Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.**





 **Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания.**

**Я не нашел как импортнусть, вот скрины схем**

![image](https://github.com/user-attachments/assets/8a32656f-c025-4f57-b1f3-9214adc3a90c)


# bug

![image](https://github.com/user-attachments/assets/a4f443b2-14fb-4e38-b63d-d2c104563e8f)


# all

![image](https://github.com/user-attachments/assets/1c00d9bb-dbf0-43f2-a942-6f314fdbc516)




















