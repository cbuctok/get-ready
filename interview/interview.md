﻿# Interview questions

## Вопросы с собеседований по SQL

### что такое SQL
Structured Query Language

### какие виды связей бывают
  - Один к одному
  - Один ко многим
  - Многие ко многим

### перечислить виды джоинов
1. INNER-JOIN: Equi-join implemetation
    ``` sql
    SELECT  *
    FROM Table1 A 
    INNER JOIN Table2 B ON A.<PrimaryKey> =B.<ForeignKey>;
    ```
1. INNER-JOIN: Natural-JOIN implementation
    ``` sql
    Select A.*, B.Col1, B.Col2          --But no B.ForiengKyeColumn in Select
    FROM Table1 A
    INNER JOIN Table2 B On A.Pk = B.Fk;
    ```
1. INNER-JOIN with NON-Eqijoin implementation
    ``` sql
    Select *
    FROM Table1 A INNER JOIN Table2 B On A.Pk <= B.Fk;
    ```
1. INNER-JOIN with SELF-JOIN
    ``` sql
    Select *
    FROM Table1 A1 INNER JOIN Table1 A2 On A1.Pk = A2.Fk;
    ```
1. OUTER JOIN (full outer join)
    ``` sql
    Select *
    FROM Table1 A FULL OUTER JOIN Table2 B On A.Pk = B.Fk;
    ```
1. LEFT JOIN
    ``` sql
    Select *
    FROM Table1 A LEFT OUTER JOIN Table2 B On A.Pk = B.Fk;
    ```
1. RIGHT JOIN
    ``` sql
    Select *
    FROM Table1 A RIGHT OUTER JOIN Table2 B On A.Pk = B.Fk;
    ```
1. CROSS JOIN
    ``` sql
    Select *
    FROM TableA CROSS JOIN TableB;
    ```
1. CROSS JOIN-Self JOIN
    ``` sql
    Select *
    FROM Table1 A1 CROSS JOIN Table1 A2;
    ```

### как используется ключевое слово having
[where vs having](https://javarevisited.blogspot.com/2013/08/difference-between-where-vs-having-clause-SQL-databse-group-by-comparision.html)

### что такое ACID
Atomicity, Consistency, Isolation, Durability

### какие есть нормальные формы
[Normal forms](https://www.geeksforgeeks.org/database-normalization-normal-forms/)
  * UNF: Unnormalized form
  * 1NF: First normal form
  * 2NF: Second normal form
  * 3NF: Third normal form
  * EKNF: Elementary key normal form
  * BCNF: Boyce–Codd normal form
  * 4NF: Fourth normal form
  * ETNF: Essential tuple normal form
  * 5NF: Fifth normal form
  * DKNF: Domain-key normal form
  * 6NF: Sixth normal form

### когда может понадобиться денормализация БД
[DB Denormalization](https://habr.com/company/latera/blog/281262/)

### для чего нужны уровни изоляции
[Isolation Levels](https://habr.com/post/317884/)
[Transaction iso](https://postgrespro.ru/docs/postgrespro/9.5/transaction-iso)

### какие феномены чтения бывают
[read phenomena](https://en.wikipedia.org/wiki/Isolation_(database_systems)#Read_phenomena)
[read phenomena (habr)](https://habr.com/company/infopulse/blog/261097/)
  1. потерянное обновление (англ. lost update) — при одновременном изменении одного блока данных разными транзакциями одно из изменений теряется;
  2. «грязное» чтение (англ. dirty read) — чтение данных, добавленных или изменённых транзакцией, которая впоследствии не подтвердится (откатится);
  3. неповторяющееся чтение (англ. non-repeatable read) — при повторном чтении в рамках одной транзакции ранее прочитанные данные оказываются изменёнными;
  4. фантомное чтение (англ. phantom reads) — одна транзакция в ходе своего выполнения несколько раз выбирает множество строк по одним и тем же критериям. Другая транзакция в интервалах между этими выборками добавляет или удаляет строки или изменяет столбцы некоторых строк, используемых в критериях выборки первой транзакции, и успешно заканчивается. В результате получится, что одни и те же выборки в первой транзакции дают разные множества строк.

## Java junior
### виды циклов
[za loopi](https://www.developer.com/java/data/using-different-types-of-java-loops-looping-in-java.html)
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

1. ```wait()``` releases the lock while
2. ```sleep()``` doesn't release any lock while waiting

The ```wait()``` is used for inter-thread communication while sleep() is used to introduce pause on execution, generally.

### что такое пул строк

[String Pool in Java](https://www.journaldev.com/797/what-is-java-string-pool)
        When we use double quotes to create a String, it first looks for String with same value in the String pool, if found it just returns the reference else it creates a new String in the pool and then returns the reference.

### почему ```String``` является immutable

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
  [Generics in Java](https://en.wikipedia.org/wiki/Generics_in_Java)

  The following block of Java code illustrates a problem that exists when not using generics. First, it declares an ArrayList of type Object. Then, it adds a String to the ArrayList. Finally, it attempts to retrieve the added String and cast it to an Integer.
  ``` java
  List v = new ArrayList();
  v.add("test");
  Integer i = (Integer)v.get(0); // Run time error
  ```
  Although the code is compiled without error, it throws a runtime exception (java.lang.ClassCastException) when executing the third line of code. This type of problem can be avoided by using generics and is the primary motivation for using generics.

  Using generics, the above code fragment can be rewritten as follows:

  ``` java
  List<String> v = new ArrayList<String>();
  v.add("test");
  Integer i = v.get(0); // (type error)  compilation-time error
  ```

### Перечислить основные принципы ООП.
  1. **Абстракция** - придание объекту характеристик, которые отличают его от всех других объектов, четко определяя его концептуальные границы.
  1. **Инкапсуляция** - свойство позволяющее пользователю не задумываться о сложности реализации используемого программного компонента (что у него внутри?), а взаимодействовать с ним посредством предоставляемого интерфейса (публичных методов и членов), а также объединить и защитить жизненно важные для компонента данные.
  1. **Наследование** - механизм позволяющий описать новый класс на основе уже существующего (родительского), при этом свойства и функциональность родительского класса заимствуются новым классом. 
  1. **Полиморфизм** - возможность объектов с одинаковой спецификацией иметь различную реализацию.

### Привести пример применения полиморфизма.
  - length()

### Какие есть модификаторы доступа?
[Acces modificators](https://metanit.com/java/tutorial/3.3.php)
  - public
  - private
  - protected
  - by default

### Что такое интерфейс?
[Interface](https://ru.stackoverflow.com/questions/136909/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D1%8B-%D0%B2-%D0%9E%D0%9E%D0%9F-java-%D0%BF%D0%BE-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%BC%D1%83)

Интерфейс — это совокупность методов и правил взаимодействия элементов системы. Другими словами, интерфейс определяет как элементы будут взаимодействовать между собой.

### Какое отличие абстрактного класса от интерфейса?
[abstract class vs interface](https://habr.com/post/30444/)

Главное отличие класса от интерфейса — в том, что класс состоит из интерфейса и реализации.

### Перечислить методы, которые присутствуют во всех объектах java.

``` java
  public Object()
  public final Class getClass()
  public int hashCode()
  public boolean equals(Object obj)
  protected Object clone() throws CloneNotSupportedException
  public String toString()
  public final void notify()
  public final void notifyAll()
  public final void wait(long timeout) throws InterruptedException
  public final void wait(long timeout, int nanoseconds) throws InterruptedException
  public final void wait() throws InterruptedException
  protected void finalize() throws Throwable
```

### Какие из них не public? Почему?
``` java
protected Object clone() throws CloneNotSupportedException
```
[Why Object class clone method is protected.](https://manjul.wordpress.com/2013/10/13/why-objects-clone-method-is-protected/)

If you want to deep cloning in that case you need to override  the clone  method  and need to  give your own implementation of clone. Rather calling super.clone you  have to copy all NON MUTABLE  fields explicitly.
``` java
protected void finalize() throws Throwable
```
The finalize method is intended to be executed by the JVM just before GC collects garbage.

### Зачем нужен метод finalize?
[JavaDoc finalize](https://docs.oracle.com/javase/7/docs/api/java/lang/Object.html#finalize%28%29)

Called by the garbage collector on an object when garbage collection determines that there are no more references to the object. A subclass overrides the finalize method to dispose of system resources or to perform other cleanup. 

### Какая связь между equals and hashcode?
[Difference between equals() and hashCode()](https://stackoverflow.com/questions/24446763/difference-between-equals-and-hashcode)
1. equals()
   
   This method checks if some other object passed to it as an argument is equal the object in which this method is invoked. 
2. hashCode()
   
   This method returns a hashCode() value as an Integer and is supported for the benefit of hashing based java.util.Collection classes like Hashtable, HashMap, HashSet etc. If a class overrides the equals() method, it must implement the hashCode() method as well.

### Рассказать иерархию исключений.

### Отличия между ArrayList и LinkedList.
[When to use LinkedList over ArrayList?](https://stackoverflow.com/questions/322715/when-to-use-linkedlist-over-arraylist)

LinkedList and ArrayList are two different implementations of the List interface. LinkedList implements it with a doubly-linked list. ArrayList implements it with a dynamically re-sizing array.



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
[Spring Security Architecture](https://spring.io/guides/topicals/spring-security-architecture/)

Authentication (who are you?) and authorization (what are you allowed to do?).

### преимущества и недостатки Spring Data
Like Hibernate but needs customization.