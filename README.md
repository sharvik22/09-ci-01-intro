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


![image](https://github.com/user-attachments/assets/db49d364-bf25-4737-9c62-2b7a54af2395)

![image](https://github.com/user-attachments/assets/63b8a307-798e-4e33-9521-28c57c04e310)

![image](https://github.com/user-attachments/assets/ecf72dd0-7696-4fbb-85e9-c61c534b5dbc)





![image](https://github.com/user-attachments/assets/3bd66cad-dab9-4587-ae4b-148d1baba33b)

# bug

![image](https://github.com/user-attachments/assets/754a8776-e593-497c-9a54-1c9b2a052ba0)

# all

![image](https://github.com/user-attachments/assets/8a8a22da-fb3f-4f22-ba3f-d8f279f7c48a)



















