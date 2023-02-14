# 28.1 Итоговая работа на сайте  Ростелеком


- Требования по проетку: https://clck.ru/32mzj7
- Объект тестирования: https://b2c.passport.rt.ru

1) Ссылка на тест-кейсы https://docs.google.com/spreadsheets/d/1K1x2_joLpuvl_XDLEU6VHoZfkR-HTobQWGtRPVzVVKk/edit?usp=sharing
2) Автоматизированное тестирование вложен на GitHub
3) Баг:
 - Во время тестирования странцы сайта зависали. Особенно во время запуска всех тестов и на середине запущенного теста страница регистрации сайта выходила ошибка и тем самым тест проваливался. Но если запускать тест отдельно, тест проходил успешно. 
 - При тестировании "Проверка названия кнопки "Продолжить" в форме "Регистрация"" тест не прошел, выходит ошибка. Подробно баг прочесть по ссылке //docs.google.com/spreadsheets/d/1K1x2_joLpuvl_XDLEU6VHoZfkR-HTobQWGtRPVzVVKk/edit?usp=sharing
 
 Тестирование приходило на основе pytest-selenium. Данным инструментом проверялось авторизация и регистрация на сайте
 
 Тест запущен с помощью pytest -v --driver Chrome --driver-path /mvideo-/Desktop/chrome/chromedriver.exe tests_rost.py
 Был скачен webdriver для Chrome версия 110.0.5481.77
 
 test_rost - описаны тесты
 settings - необходимые данные для теста 
