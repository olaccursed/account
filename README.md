# Тестовое задание 

Реализовать при помощи объектно-ориентированного подхода сущность "Счет". 
Счет имеет следующие поля: 
  1) Номер (приватное)
  2) Статус (приватное)
  3) Дата
  4) Скидка
  5) Состав счета (каждая позиция имеет 4 поля: id, сумма, количество и название)
Операции, производимые со счетом:
  1) Получить или установить поля "Номер", "Статус", "Дата", "Скидка"
  2) Добавить или удалить позицию в счете
  3) Получить сумму счета на основе его состава и скидки
  
Будет "+", если состав счета будет реализован с помощью ООП, а не массивом.

Каждый счет хранится в БД MySQL (архитектуру таблиц придумать самому). 

Написать PHP-скрипт получения счетов из БД в статусе "Оплачен" и с датой больше 01.01.2020. 
Какие варианты оптимизации предложите для достижения наибольшей производительности в случае слишком большого количества записей