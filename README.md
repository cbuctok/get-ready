﻿- [Interview questions](#interview-questions)
  - [Вопросы с собеседований по SQL](#%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D1%8B-%D1%81-%D1%81%D0%BE%D0%B1%D0%B5%D1%81%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B9-%D0%BF%D0%BE-sql)
    - [что такое SQL](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-sql)
    - [какие виды связей бывают](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B2%D0%B8%D0%B4%D1%8B-%D1%81%D0%B2%D1%8F%D0%B7%D0%B5%D0%B9-%D0%B1%D1%8B%D0%B2%D0%B0%D1%8E%D1%82)
    - [перечислить виды джоинов](#%D0%BF%D0%B5%D1%80%D0%B5%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D1%8C-%D0%B2%D0%B8%D0%B4%D1%8B-%D0%B4%D0%B6%D0%BE%D0%B8%D0%BD%D0%BE%D0%B2)
    - [как используется ключевое слово having](#%D0%BA%D0%B0%D0%BA-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D1%83%D0%B5%D1%82%D1%81%D1%8F-%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-having)
    - [что такое ACID](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-acid)
    - [какие есть нормальные формы](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B5%D1%81%D1%82%D1%8C-%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%84%D0%BE%D1%80%D0%BC%D1%8B)
    - [когда может понадобиться денормализация БД](#%D0%BA%D0%BE%D0%B3%D0%B4%D0%B0-%D0%BC%D0%BE%D0%B6%D0%B5%D1%82-%D0%BF%D0%BE%D0%BD%D0%B0%D0%B4%D0%BE%D0%B1%D0%B8%D1%82%D1%8C%D1%81%D1%8F-%D0%B4%D0%B5%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D0%B1%D0%B4)
    - [для чего нужны уровни изоляции](#%D0%B4%D0%BB%D1%8F-%D1%87%D0%B5%D0%B3%D0%BE-%D0%BD%D1%83%D0%B6%D0%BD%D1%8B-%D1%83%D1%80%D0%BE%D0%B2%D0%BD%D0%B8-%D0%B8%D0%B7%D0%BE%D0%BB%D1%8F%D1%86%D0%B8%D0%B8)
    - [какие феномены чтения бывают](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D1%84%D0%B5%D0%BD%D0%BE%D0%BC%D0%B5%D0%BD%D1%8B-%D1%87%D1%82%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B1%D1%8B%D0%B2%D0%B0%D1%8E%D1%82)
  - [Java junior](#java-junior)
    - [виды циклов za loopi](#%D0%B2%D0%B8%D0%B4%D1%8B-%D1%86%D0%B8%D0%BA%D0%BB%D0%BE%D0%B2-za-loopi)
    - [что такое рекурсия](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D1%80%D0%B5%D0%BA%D1%83%D1%80%D1%81%D0%B8%D1%8F)
    - [отличие final, finally, finalize](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-final-finally-finalize)
    - [что такое try-with-resource](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-try-with-resource)
    - [отличие wait(100) от sleep(100)](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-wait100-%D0%BE%D1%82-sleep100)
    - [что такое пул строк](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%BF%D1%83%D0%BB-%D1%81%D1%82%D1%80%D0%BE%D0%BA)
    - [почему String является immutable](#%D0%BF%D0%BE%D1%87%D0%B5%D0%BC%D1%83-string-%D1%8F%D0%B2%D0%BB%D1%8F%D0%B5%D1%82%D1%81%D1%8F-immutable)
    - [какие виды деревьев существуют](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B2%D0%B8%D0%B4%D1%8B-%D0%B4%D0%B5%D1%80%D0%B5%D0%B2%D1%8C%D0%B5%D0%B2-%D1%81%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D1%83%D1%8E%D1%82)
    - [примеры применения деревьев](#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D1%8B-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B4%D0%B5%D1%80%D0%B5%D0%B2%D1%8C%D0%B5%D0%B2)
    - [рассказать, как работает HashMap](#%D1%80%D0%B0%D1%81%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C-%D0%BA%D0%B0%D0%BA-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D0%B5%D1%82-hashmap)
      - [Put](#put)
      - [Get](#get)
    - [что такое автобоксинг](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%B0%D0%B2%D1%82%D0%BE%D0%B1%D0%BE%D0%BA%D1%81%D0%B8%D0%BD%D0%B3)
    - [рассказать про алгоритмы сортировки и их сложности](#%D1%80%D0%B0%D1%81%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C-%D0%BF%D1%80%D0%BE-%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%D1%8B-%D1%81%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B8-%D0%B8-%D0%B8%D1%85-%D1%81%D0%BB%D0%BE%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
    - [для чего нужны дженерики](#%D0%B4%D0%BB%D1%8F-%D1%87%D0%B5%D0%B3%D0%BE-%D0%BD%D1%83%D0%B6%D0%BD%D1%8B-%D0%B4%D0%B6%D0%B5%D0%BD%D0%B5%D1%80%D0%B8%D0%BA%D0%B8)
    - [Перечислить основные принципы ООП.](#%D0%BF%D0%B5%D1%80%D0%B5%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D1%8C-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BF%D1%80%D0%B8%D0%BD%D1%86%D0%B8%D0%BF%D1%8B-%D0%BE%D0%BE%D0%BF)
    - [Привести пример применения полиморфизма.](#%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D1%81%D1%82%D0%B8-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BF%D0%BE%D0%BB%D0%B8%D0%BC%D0%BE%D1%80%D1%84%D0%B8%D0%B7%D0%BC%D0%B0)
    - [Какие есть модификаторы доступа?](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B5%D1%81%D1%82%D1%8C-%D0%BC%D0%BE%D0%B4%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0)
    - [Что такое интерфейс?](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81)
    - [Какое отличие абстрактного класса от интерфейса?](#%D0%BA%D0%B0%D0%BA%D0%BE%D0%B5-%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-%D0%B0%D0%B1%D1%81%D1%82%D1%80%D0%B0%D0%BA%D1%82%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B0-%D0%BE%D1%82-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D0%B0)
    - [Перечислить методы, которые присутствуют во всех объектах java.](#%D0%BF%D0%B5%D1%80%D0%B5%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D1%8C-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D0%B5-%D0%BF%D1%80%D0%B8%D1%81%D1%83%D1%82%D1%81%D1%82%D0%B2%D1%83%D1%8E%D1%82-%D0%B2%D0%BE-%D0%B2%D1%81%D0%B5%D1%85-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%B0%D1%85-java)
    - [Какие из них не public? Почему?](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B8%D0%B7-%D0%BD%D0%B8%D1%85-%D0%BD%D0%B5-public-%D0%BF%D0%BE%D1%87%D0%B5%D0%BC%D1%83)
    - [Зачем нужен метод finalize?](#%D0%B7%D0%B0%D1%87%D0%B5%D0%BC-%D0%BD%D1%83%D0%B6%D0%B5%D0%BD-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4-finalize)
    - [Какая связь между equals and hashcode?](#%D0%BA%D0%B0%D0%BA%D0%B0%D1%8F-%D1%81%D0%B2%D1%8F%D0%B7%D1%8C-%D0%BC%D0%B5%D0%B6%D0%B4%D1%83-equals-and-hashcode)
    - [Рассказать иерархию исключений.](#%D1%80%D0%B0%D1%81%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C-%D0%B8%D0%B5%D1%80%D0%B0%D1%80%D1%85%D0%B8%D1%8E-%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D0%B9)
    - [Отличия между ArrayList и LinkedList.](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D1%8F-%D0%BC%D0%B5%D0%B6%D0%B4%D1%83-arraylist-%D0%B8-linkedlist)
  - [Java middle](#java-middle)
    - [Отличие HashMap от TreeMap](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-hashmap-%D0%BE%D1%82-treemap)
    - [Кэширование в Hibernate](#%D0%BA%D1%8D%D1%88%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B2-hibernate)
    - [Наследование в Hibernate](#%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B2-hibernate)
    - [Скоупы Spring бинов](#%D1%81%D0%BA%D0%BE%D1%83%D0%BF%D1%8B-spring-%D0%B1%D0%B8%D0%BD%D0%BE%D0%B2)
    - [Отличие singletone от prototype](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-singletone-%D0%BE%D1%82-prototype)
    - [Жизненный цикл в Maven](#%D0%B6%D0%B8%D0%B7%D0%BD%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-%D1%86%D0%B8%D0%BA%D0%BB-%D0%B2-maven)
    - [Отличие install от deploy](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-install-%D0%BE%D1%82-deploy)
    - [Минусы TDD](#%D0%BC%D0%B8%D0%BD%D1%83%D1%81%D1%8B-tdd)
    - [Collection – основные интерфейсы](#collection-%E2%80%93-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D1%8B)
    - [Зачем нужно красно-чёрное дерево в Джаве](#%D0%B7%D0%B0%D1%87%D0%B5%D0%BC-%D0%BD%D1%83%D0%B6%D0%BD%D0%BE-%D0%BA%D1%80%D0%B0%D1%81%D0%BD%D0%BE-%D1%87%D1%91%D1%80%D0%BD%D0%BE%D0%B5-%D0%B4%D0%B5%D1%80%D0%B5%D0%B2%D0%BE-%D0%B2-%D0%B4%D0%B6%D0%B0%D0%B2%D0%B5)
    - [Есть одна таблица в БД и три сущности. Как осуществить маппинг с помощью JPA/Hibernate](#%D0%B5%D1%81%D1%82%D1%8C-%D0%BE%D0%B4%D0%BD%D0%B0-%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0-%D0%B2-%D0%B1%D0%B4-%D0%B8-%D1%82%D1%80%D0%B8-%D1%81%D1%83%D1%89%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%BA%D0%B0%D0%BA-%D0%BE%D1%81%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B8%D1%82%D1%8C-%D0%BC%D0%B0%D0%BF%D0%BF%D0%B8%D0%BD%D0%B3-%D1%81-%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E-jpahibernate)
    - [Уровни кэширования в Hibernate. Чем они отличаются](#%D1%83%D1%80%D0%BE%D0%B2%D0%BD%D0%B8-%D0%BA%D1%8D%D1%88%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%B2-hibernate-%D1%87%D0%B5%D0%BC-%D0%BE%D0%BD%D0%B8-%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B0%D1%8E%D1%82%D1%81%D1%8F)
    - [Какие есть сторонние решения для кэширования](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B5%D1%81%D1%82%D1%8C-%D1%81%D1%82%D0%BE%D1%80%D0%BE%D0%BD%D0%BD%D0%B8%D0%B5-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B4%D0%BB%D1%8F-%D0%BA%D1%8D%D1%88%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)
    - [Рассказать про Inversion of Control Containers и Dependency Injection](#%D1%80%D0%B0%D1%81%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C-%D0%BF%D1%80%D0%BE-inversion-of-control-containers-%D0%B8-dependency-injection)
    - [Spring – какие есть скоупы и для чего используются](#spring-%E2%80%93-%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B5%D1%81%D1%82%D1%8C-%D1%81%D0%BA%D0%BE%D1%83%D0%BF%D1%8B-%D0%B8-%D0%B4%D0%BB%D1%8F-%D1%87%D0%B5%D0%B3%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D1%83%D1%8E%D1%82%D1%81%D1%8F)
    - [TDD и BDD](#tdd-%D0%B8-bdd)
    - [Для чего нужен Mockito](#%D0%B4%D0%BB%D1%8F-%D1%87%D0%B5%D0%B3%D0%BE-%D0%BD%D1%83%D0%B6%D0%B5%D0%BD-mockito)
    - [Отличие Mock от Spy](#%D0%BE%D1%82%D0%BB%D0%B8%D1%87%D0%B8%D0%B5-mock-%D0%BE%D1%82-spy)
    - [Этапы сборки проекта](#%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B8-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)
  - [Java spring](#java-spring)
    - [что такое Spring](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-spring)
    - [как понимаете Dependency Injection](#%D0%BA%D0%B0%D0%BA-%D0%BF%D0%BE%D0%BD%D0%B8%D0%BC%D0%B0%D0%B5%D1%82%D0%B5-dependency-injection)
    - [как понимаете Inversion of Control](#%D0%BA%D0%B0%D0%BA-%D0%BF%D0%BE%D0%BD%D0%B8%D0%BC%D0%B0%D0%B5%D1%82%D0%B5-inversion-of-control)
    - [примеры DI и IoC](#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D1%8B-di-%D0%B8-ioc)
    - [что такое бин Spring’е](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%B1%D0%B8%D0%BD-spring%D0%B5)
    - [какие есть scope у бина](#%D0%BA%D0%B0%D0%BA%D0%B8%D0%B5-%D0%B5%D1%81%D1%82%D1%8C-scope-%D1%83-%D0%B1%D0%B8%D0%BD%D0%B0)
    - [можно ли задать свой scope](#%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE-%D0%BB%D0%B8-%D0%B7%D0%B0%D0%B4%D0%B0%D1%82%D1%8C-%D1%81%D0%B2%D0%BE%D0%B9-scope)
    - [жизненный цикл бина](#%D0%B6%D0%B8%D0%B7%D0%BD%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-%D1%86%D0%B8%D0%BA%D0%BB-%D0%B1%D0%B8%D0%BD%D0%B0)
    - [что такое жизненный цикл бина](#%D1%87%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-%D0%B6%D0%B8%D0%B7%D0%BD%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-%D1%86%D0%B8%D0%BA%D0%BB-%D0%B1%D0%B8%D0%BD%D0%B0)
    - [можно ли добавить бин, если приложение уже стартануло](#%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE-%D0%BB%D0%B8-%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%B8%D1%82%D1%8C-%D0%B1%D0%B8%D0%BD-%D0%B5%D1%81%D0%BB%D0%B8-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5-%D1%83%D0%B6%D0%B5-%D1%81%D1%82%D0%B0%D1%80%D1%82%D0%B0%D0%BD%D1%83%D0%BB%D0%BE)
    - [как получить объекты ServletContext и ServletConfig](#%D0%BA%D0%B0%D0%BA-%D0%BF%D0%BE%D0%BB%D1%83%D1%87%D0%B8%D1%82%D1%8C-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D1%8B-servletcontext-%D0%B8-servletconfig)
    - [виды внедрения зависимостей](#%D0%B2%D0%B8%D0%B4%D1%8B-%D0%B2%D0%BD%D0%B5%D0%B4%D1%80%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B7%D0%B0%D0%B2%D0%B8%D1%81%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B5%D0%B9)
    - [для чего нужна аннотация @Qualifier](#%D0%B4%D0%BB%D1%8F-%D1%87%D0%B5%D0%B3%D0%BE-%D0%BD%D1%83%D0%B6%D0%BD%D0%B0-%D0%B0%D0%BD%D0%BD%D0%BE%D1%82%D0%B0%D1%86%D0%B8%D1%8F-qualifier)
    - [разница между аннотациями @Component, @Repository, @Service](#%D1%80%D0%B0%D0%B7%D0%BD%D0%B8%D1%86%D0%B0-%D0%BC%D0%B5%D0%B6%D0%B4%D1%83-%D0%B0%D0%BD%D0%BD%D0%BE%D1%82%D0%B0%D1%86%D0%B8%D1%8F%D0%BC%D0%B8-component-repository-service)
    - [как работает транзакция в Spring](#%D0%BA%D0%B0%D0%BA-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D0%B5%D1%82-%D1%82%D1%80%D0%B0%D0%BD%D0%B7%D0%B0%D0%BA%D1%86%D0%B8%D1%8F-%D0%B2-spring)
    - [что знаете о DispatcherServlet и ContextLoaderListener](#%D1%87%D1%82%D0%BE-%D0%B7%D0%BD%D0%B0%D0%B5%D1%82%D0%B5-%D0%BE-dispatcherservlet-%D0%B8-contextloaderlistener)
    - [рассказать как устроен Spring MVC](#%D1%80%D0%B0%D1%81%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D1%8C-%D0%BA%D0%B0%D0%BA-%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD-spring-mvc)
    - [для чего нужны аннотации @RequestBody, @PathVariable, @RequestParam](#%D0%B4%D0%BB%D1%8F-%D1%87%D0%B5%D0%B3%D0%BE-%D0%BD%D1%83%D0%B6%D0%BD%D1%8B-%D0%B0%D0%BD%D0%BD%D0%BE%D1%82%D0%B0%D1%86%D0%B8%D0%B8-requestbody-pathvariable-requestparam)
    - [что лежит в основе Spring Security](#%D1%87%D1%82%D0%BE-%D0%BB%D0%B5%D0%B6%D0%B8%D1%82-%D0%B2-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5-spring-security)
    - [преимущества и недостатки Spring Data](#%D0%BF%D1%80%D0%B5%D0%B8%D0%BC%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B0-%D0%B8-%D0%BD%D0%B5%D0%B4%D0%BE%D1%81%D1%82%D0%B0%D1%82%D0%BA%D0%B8-spring-data)

# Interview questions

## Вопросы с собеседований по SQL

### что такое SQL
Structured Query Language

### какие виды связей бывают

### перечислить виды джоинов

### как используется ключевое слово having
[where vs having](https://javarevisited.blogspot.com/2013/08/difference-between-where-vs-having-clause-SQL-databse-group-by-comparision.html)

### что такое ACID
Atomicity, Consistency, Isolation, Durability

### какие есть нормальные формы

### когда может понадобиться денормализация БД
[link](https://habr.com/company/latera/blog/281262/)

### для чего нужны уровни изоляции
[link1](https://habr.com/post/317884/)
[link2](https://postgrespro.ru/docs/postgrespro/9.5/transaction-iso)

### какие феномены чтения бывают
[read phenomena](https://en.wikipedia.org/wiki/Isolation_(database_systems)#Read_phenomena)
[link](https://habr.com/company/infopulse/blog/261097/)
1. потерянное обновление (англ. lost update) — при одновременном изменении одного блока данных разными транзакциями одно из изменений теряется;
2. «грязное» чтение (англ. dirty read) — чтение данных, добавленных или изменённых транзакцией, которая впоследствии не подтвердится (откатится);
3. неповторяющееся чтение (англ. non-repeatable read) — при повторном чтении в рамках одной транзакции ранее прочитанные данные оказываются изменёнными;
4. фантомное чтение (англ. phantom reads) — одна транзакция в ходе своего выполнения несколько раз выбирает множество строк по одним и тем же критериям. Другая транзакция в интервалах между этими выборками добавляет или удаляет строки или изменяет столбцы некоторых строк, используемых в критериях выборки первой транзакции, и успешно заканчивается. В результате получится, что одни и те же выборки в первой транзакции дают разные множества строк.

## Java junior
### виды циклов [za loopi](https://www.developer.com/java/data/using-different-types-of-java-loops-looping-in-java.html)
1. while
2. for
3. do..while

### что такое рекурсия
хуйня ибаная (см. java junior #2)

### отличие final, finally, finalize
[final, finally, finalize](http://javaway.info/v-chyom-otlichie-final-finally-finalize/)
1. Final class can't be inherited, final method can't be overridden and final variable value can't be changed.
2. Finally is used to place important code, it will be executed whether exception is handled or not.
3. Finalize is used to perform clean up processing just before object is garbage collected.

### что такое try-with-resource
[java doc](https://docs.oracle.com/javase/tutorial/essential/exceptions/tryResourceClose.html)
The try-with-resources statement is a try statement that declares one or more resources. A resource is an object that must be closed after the program is finished with it.

### отличие wait(100) от sleep(100)

1. wait() releases the lock while
2. sleep() doesn't release any lock while waiting

The wait() is used for inter-thread communication while sleep() is used to introduce pause on execution, generally.

### что такое пул строк

[String Pool in Java](https://www.journaldev.com/797/what-is-java-string-pool)
        When we use double quotes to create a String, it first looks for String with same value in the String pool, if found it just returns the reference else it creates a new String in the pool and then returns the reference.

### почему String является immutable

[because](https://stackoverflow.com/questions/22397861/why-is-string-immutable-in-java)

1. Requirement of String Pool
2. Allow String to Cache its Hashcode
3. Security

### какие виды деревьев существуют

### примеры применения деревьев

### рассказать, как работает HashMap

[HashMap explanation](https://www.geeksforgeeks.org/internal-working-of-hashmap-java/)

#### Put
  - Calculate hash code of Key ```{“Key LOL”}```. It will be generated as ```118```.
  - Calculate index by using index method it will be ```6```.
  - Create a node object as:  
  ``` java
  {
  int hash = 118
  Key key = {"Key LOL"}
  Integer value = 40
  Node next = null
  }
  ```
  - Place this object at index ```6``` if no other object is presented there.
  - In this case a node object is found at the index ```6``` – this is a case of collision.
  - In that case, check via ```hashCode()``` and ```equals()``` method that if both the keys are same.
  - If keys are same, replace the value with current value.
  - Otherwise connect this node object to the previous node object via linked list and both are stored at index ```6```.
#### Get
  - Calculate hash code of Key ```{“Key LOL"}```. It will be generated as ```115```.
  - Calculate index by using index method it will be ```3```.
  - Go to index ```3``` of array and compare first element’s key with given key. If both are equals then return the value, otherwise check for next element if it exists.
  - In our case it is found as first element and returned value is ```30```.

### что такое автобоксинг

[JavaDoc](https://docs.oracle.com/javase/tutorial/java/data/autoboxing.html)
Autoboxing is the automatic conversion that the Java compiler makes between the primitive types and their corresponding object wrapper classes. For example, converting an int to an Integer, a double to a Double, and so on. If the conversion goes the other way, this is called *unboxing*.

### рассказать про алгоритмы сортировки и их сложности

### для чего нужны дженерики

### Перечислить основные принципы ООП.
  1. **Абстракция** - придание объекту характеристик, которые отличают его от всех других объектов, четко определяя его концептуальные границы.
  1. **Инкапсуляция** - свойство позволяющее пользователю не задумываться о сложности реализации используемого программного компонента (что у него внутри?), а взаимодействовать с ним посредством предоставляемого интерфейса (публичных методов и членов), а также объединить и защитить жизненно важные для компонента данные.
  1. **Наследование** - механизм позволяющий описать новый класс на основе уже существующего (родительского), при этом свойства и функциональность родительского класса заимствуются новым классом. 
  1. **Полиморфизм** - возможность объектов с одинаковой спецификацией иметь различную реализацию.

### Привести пример применения полиморфизма.
  - length()

### Какие есть модификаторы доступа?
[модификаторы доступа](https://metanit.com/java/tutorial/3.3.php)
  - public
  - private
  - protected
  - by default

### Что такое интерфейс?
[интерфейс](https://ru.stackoverflow.com/questions/136909/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D1%8B-%D0%B2-%D0%9E%D0%9E%D0%9F-java-%D0%BF%D0%BE-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%BC%D1%83)

### Какое отличие абстрактного класса от интерфейса?
[святой хабр](https://habr.com/post/30444/)

### Перечислить методы, которые присутствуют во всех объектах java.

### Какие из них не public? Почему?

### Зачем нужен метод finalize?

### Какая связь между equals and hashcode?

### Рассказать иерархию исключений.

### Отличия между ArrayList и LinkedList.

## Java middle
 
### Отличие HashMap от TreeMap

### Кэширование в Hibernate

### Наследование в Hibernate

### Скоупы Spring бинов

### Отличие singletone от prototype

### Жизненный цикл в Maven

### Отличие install от deploy

### Минусы TDD

### Collection – основные интерфейсы

### Зачем нужно красно-чёрное дерево в Джаве

A red–black tree is a kind of self-balancing binary search tree
Each node is either red or black.
The root is black. This rule is sometimes omitted. Since the root can always be changed from red to black, but not necessarily vice versa, this rule has little effect on analysis.
All leaves (NIL) are black.
If a node is red, then both its children are black.
Every path from a given node to any of its descendant NIL nodes contains the same number of black nodes.

### Есть одна таблица в БД и три сущности. Как осуществить маппинг с помощью JPA/Hibernate

### Уровни кэширования в Hibernate. Чем они отличаются

### Какие есть сторонние решения для кэширования

### Рассказать про Inversion of Control Containers и Dependency Injection

### Spring – какие есть скоупы и для чего используются

### TDD и BDD

### Для чего нужен Mockito

### Отличие Mock от Spy

### Этапы сборки проекта

## Java spring

### что такое Spring

### как понимаете Dependency Injection

[Dependancy Injection](http://www.vogella.com/tutorials/DependencyInjection/article.html)

Class should not configure its dependencies statically but should be configured from the outside.
If the Java class creates an instance of another class via the new operator, it cannot be used (and tested) independently from this class and this is called a hard dependency.
A framework class, usually called the dependency container, could analyze the dependencies of this class.
The standard Java annotations for describing the dependencies of a class are defined in the Java Specification Request 330 (JSR330). This specification describes the @Inject and @Named annotations.
According to JSR330 the injection is done in the following order:
- constructor injection
- field injection
- method injection

### как понимаете Inversion of Control

### примеры DI и IoC

### что такое бин Spring’е

### какие есть scope у бина

### можно ли задать свой scope

### жизненный цикл бина

### что такое жизненный цикл бина

### можно ли добавить бин, если приложение уже стартануло

### как получить объекты ServletContext и ServletConfig

### виды внедрения зависимостей

### для чего нужна аннотация @Qualifier

### разница между аннотациями @Component, @Repository, @Service

### как работает транзакция в Spring

### что знаете о DispatcherServlet и ContextLoaderListener

### рассказать как устроен Spring MVC

### для чего нужны аннотации @RequestBody, @PathVariable, @RequestParam

### что лежит в основе Spring Security

### преимущества и недостатки Spring Data
