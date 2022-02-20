Проект по автоматизации на python+SeleniumWEB+pyTest+PageObject по курсу "Автоматизация тестирования с помощью Selenium и Python" https://stepik.org/course/575/info

Краткое описание файлов:

base_page.py - тут мы храним методы которые применяются по всему проекту вообще, всё завернуто в класс, чтобы было удобно импортировать.

locators.py - тут мы храним локаторы, в виде констант. Локаторы каждой отдельной страницы завёрнуты в класс, чтобы было удобно импортировать

main_page,login_page, product_page - тут мы храним методы по конкретной странице, завернутые в класс этой странице. Классы MainPage,LoginPage, ProductPage - наследники класса BasePage, чтобы можно было пользоваться методами, описанными в base_page.py

test_main_page.py и test_product_page - собственно сами тест-кейсы который мы прогоняем pyTest


