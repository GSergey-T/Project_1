## Проект "Электронная библиотека"
### Описание:
Электронная библиотека представляет собой цифровой учёт книг.
Пользователь имеет возможность регистрировать читателей, добавлять книги,
выдавать книги читателям и освобождать их.
### Функционал:

0) Начальная страница

   ![](Screenshots/img1.png)
   
1) Страница добавления, изменения и удаления книги (аналогично с человеком).

   ![](Screenshots/img4.png)
   -
   ![](Screenshots/img5.png)

2) Страница со списком всех людей (люди кликабельные - при клике осуществляется
   переход на страницу человека).

   ![](Screenshots/img2.png)

3) Страница со списком всех книг (книги кликабельные - при клике осуществляется
   переход на страницу книги).

   ![](Screenshots/img3.png)

4) Если человек не взял ни одной книги, отображается текст текст "Человек
   пока не взял ни одной книги". Если книга назначена человеку, то у него отображаются назначенные книги.

   ![](Screenshots/img6.png)
   -
   ![](Screenshots/img7.png)

5) Если книга свободна, то отображается выпадающий список
   со всеми людьми и кнопка "Назначить книгу". Эта кнопка нажимается библиотекарем
   тогда, когда читатель хочет забрать эту книгу домой. После нажатия на эту кнопку, книга
   принадлежит выбранному человеку и появляется в его списке
   книг.

   ![](Screenshots/img8.png)
   -
   ![](Screenshots/img9.png)

6) Все поля валидируются с помощью @Valid и Spring Validator (сделана проверка на уникальность ФИО)
    
   ![](Screenshots/img10.png)
   -
   ![](Screenshots/img11.png)
### Сущности:
- Человек
- Книга

Связь: Один ко многим

   ![](Screenshots/img.png)

### Реализовано с использованием Spring Framework:
- Spring Core
- Spring MVC
- JdbcTemplate

База данных: PostreSQL
