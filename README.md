# Homework2Java
Приложением пользуется администратор

Данные для входа: 

Пароль: 1234

Логин: superuser

Когда администратро вошел под своими данными, открывается страница где можно выбрать кого необходимо внести в базу данных: родителя или ребенка


1. Вводим родителя (заполняем ФИО, выбираем улицу проживания). Можем редактировать информацию. 
	Так же есть возможность добавить ребенка (но для этого он уже должен быть заведен в БД)
2. Вводим ребёнка (заполняем ФИО и возраст) Затем добовляем у родителя ребенка 
	и после этого у ребенка появляется возможность выбрать учебное заведение (список соответствует  месту проживания родителя)


Такие данные как адреса проживания, номера школ и соотношение районов-школ уже есть в коде и ручного ввода не требуют.

+ Добавлены проверочные тест записи/выбора/чтения без использования JPA. (OtherTests) 
