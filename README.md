# Домашнее задание

## Урок №1
### Задание
1. Все задания с практики должны быть 
выполнены и загружены в репозиторий. В 
качестве выполненного домашнего задания 
присылайте ссылку на pull request. 
Рекомендуется github, но можно использовать 
любой. Помните, что это ваш будущий проект, 
который вы будете защищать перед будущим 
работодателем, поэтому относитесь к нему 
соответствующе.
2. Пришлите содержимое вашего crontab 
сообщением (вывод команды crontab -l)
3. Опишите результат взаимодействия с 
systemctl. Как вы считаете в каких задачах 
использование демонов лучше, чем 
использование crontab?
4. ⚹ Запустить демон с помощью systemd, вместо 
systemctl. Допустимо написать только 
worker.service файл.

## Урок №2
### Задание 
1. Сделайте новую ветку из той, которую мы 
создали на прошлом уроке. Это нужно для 
того, чтобы мы могли работать с кодом из 
прошлого урока.
2. Загрузите весь код из сегодняшнего урока в 
Git в новую ветку, создайте новый pull request. 
Пришлите на проверку ссылку на pull request.
3. Сегодня мы работали с вами с токеном 
Telegram. Какой тип аутентификации мы 
использовали? 
4. ⚹ На занятии мы создали класс 
TgMessagesCommand. Сделайте так, чтобы он 
мог общаться с пользователем и запрашивать 
данные для сохранения расписания.

##Урок №3
### Задание
1. Сделайте новую ветку из той, которую мы создали на 
прошлом уроке. Это нужно для того, чтобы мы могли 
работать с кодом из прошлого урока.
2. Загрузите весь код из сегодняшнего урока в Git в новую 
ветку, создайте новый pull request. Пришлите на проверку 
ссылку на pull request.
3. ⚹ Создайте тесты на оставшиеся контракты, которые мы 
придумали на уроке. Знаете еще сценарии, на которые 
можно написать unit-тест? Сделайте это! 
4. ⚹ Сломайте некоторые тесты и постарайтесь получить все 
типы результатов, которые мы разобрали в лекции.
5. ⚹ На уроке мы рассмотрели много сценариев, на которые 
мы не можем создать тесты, т.к. они содержат побочные 
эффекты (соединяются с базой данных или с сервером 
telegram). Подумайте, как мы можем изменить код нашего 
приложения, чтобы создать unit-тест стало возможно.
