# Домашнее задание к занятию "09.01 Жизненный цикл ПО"

## Подготовка к выполнению
1. Получить бесплатную [JIRA](https://www.atlassian.com/ru/software/jira/free)
2. Настроить её для своей "команды разработки"
3. Создать доски kanban и scrum

#### Ответ: подготовка выполнена.

## Основная часть
В рамках основной части необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить следующий жизненный цикл:
1. Open -> On reproduce
2. On reproduce <-> Open, Done reproduce
3. Done reproduce -> On fix
4. On fix <-> On reproduce, Done fix
5. Done fix -> On test
6. On test <-> On fix, Done
7. Done <-> Closed, Open

#### Ответ:

![image](https://user-images.githubusercontent.com/92969676/170458243-cb3a0aa8-506c-43ef-b407-8adf04697d00.png)


Остальные задачи должны проходить по упрощённому workflow:
1. Open -> On develop
2. On develop <-> Open, Done develop
3. Done develop -> On test
4. On test <-> On develop, Done
5. Done <-> Closed, Open

#### Ответ:

![image](https://user-images.githubusercontent.com/92969676/170458123-88efe350-f2fe-496f-bb86-8e8ddea58ec2.png)


Создать задачу с типом bug, попытаться провести его по всему workflow до Done. Создать задачу с типом epic, к ней привязать несколько задач с типом task, провести их по всему workflow до Done. При проведении обеих задач по статусам использовать kanban. Вернуть задачи в статус Open.
Перейти в scrum, запланировать новый спринт, состоящий из задач эпика и одного бага, стартовать спринт, провести задачи до состояния Closed. Закрыть спринт.

Если всё отработало в рамках ожидания - выгрузить схемы workflow для импорта в XML. Файлы с workflow приложить к решению задания.

#### Ответ:

Просто накидаю немного скриншотов, "как всё это было":

![image](https://user-images.githubusercontent.com/92969676/170457994-53cc6ad3-ef8e-4f4f-b5d3-296f57c85a29.png)

![image](https://user-images.githubusercontent.com/92969676/170457248-df87123f-2e72-44e0-aa36-530355bd93ad.png)

![image](https://user-images.githubusercontent.com/92969676/170457330-a477e225-ccc3-44a0-a846-f457ac215546.png)

![image](https://user-images.githubusercontent.com/92969676/170457422-062deadf-02a6-40e8-83c5-0fa7cba91cf5.png)

![image](https://user-images.githubusercontent.com/92969676/170457504-95c3e87d-de50-41ca-88a2-c353e06cd9cc.png)

![image](https://user-images.githubusercontent.com/92969676/170457646-274f6182-138d-4a42-b55f-74009a22bd29.png)

![image](https://user-images.githubusercontent.com/92969676/170462990-e1fe25ff-ccb2-4dd8-971d-18eada276512.png)

![image](https://user-images.githubusercontent.com/92969676/170462824-5b3c5a01-c6ca-4a81-bd47-f2af99f1dd16.png)

XML-Файл со схемами выгрузил и приложил в репозитории.
