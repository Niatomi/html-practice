# HTML Практика

## Упражнение 1. Структура страницы

### Задачи:

- Объединить самостоятельные элементы так, чтобы они формировали структуру HTML-страницы.

### Исходные данные:

```
<body></body> <html></html> <head></head> <title>Первая страница</title>
<p>Моя первая HTML страница</p> <DOCTYPE html> <meta charset="utf-8">
```

---

## Упражнение 2. Текст

### Задачи:

1. Разметить представленный текст у себя в редакторе так, чтобы результат выглядел как в исходных данных, используя теги заголовка и абзаца (h1 p)

2. Превратить первый перечень в неупорядоченный список, а второй в упорядоченный (ol ul li)

3. Превратить первый перечень в неупорядоченный список, а второй в упорядоченный (ol ul li)

### Исходные данные:

```
Введение

Чтобы создавать веб-сайты, вы должны знать о HTML (HyperText Markup Language / Язык гипертекстовой разметки)  — фундаментальной технологии, которая используется для определения структуры веб-страницы.

HTML применяется для того, чтобы определить как должен отображаться ваш контент в различном виде:

Абзац Список Заголовок Ссылка Изображение Мультимедиа Формы

Существует множество и других доступных элементов, также вы можете создать свой собственный новый элемент.

Темы для изучения

Для того чтобы создать свою первую страницу с помощью HTML нужно понимать некоторые темы:

Работа с текстом Атрибуты Ссылки Изображения Таблицы Формы
```

### Результат работы HTML:

<p align="left">
  <img src="https://vladilen.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fb4cc05af-7cfc-4fde-afed-46021c0d4af5%2FUntitled.png?table=block&id=53672cd3-f006-4f06-93d8-4ebf9b0d229f&spaceId=4c8a7a76-f839-431a-aed6-1f9189e1c691&width=2000&userId=&cache=v2" width="600px">
</p>

---

### Упражнение 3. Гиперссылки

### Задачи:

1. Создать html страницу как в [упражнении №1](https://www.notion.so/08d9c5797bf3446db67176f15fff23b3) поместить текст из исходных данных

2. Создать необходимые ссылки в ниже представленном тексте так, чтобы они указывали на соответствующие страницы (`a`) Примечание: для внешних страниц используйте атрибут `target`

3. Реализовать ссылку для открытия почтового сервиса и заданием темы письма

### Исходные данные:

```
Сейчас мы выполняем упражнение 3

Сделаем ссылку для слова телеграм (https://t.me/js_by_vladilen)
Сделаем ссылку на слово YouTube (https://www.youtube.com/c/VladilenMinin)
Сделаем ссылку на слово Instagram (https://www.instagram.com/vladilen.minin/)

Добавим ссылку на ваш почтовый адрес email@gmai.com
```

---

### Упражнение 4. Изображения

### Задачи

1. Создать html страницу как в [упражнении №1](https://www.notion.so/08d9c5797bf3446db67176f15fff23b3) поместить текст из исходных данных

2. Вставьте изображение разных форматов: png, jps,gif, svg (`img`)

3. Вставить изображение логотипа YouTube и реализовать переход на сайт YouTube по клику на картинку.

### Исходные данные:

```
Сейчас мы выполняем упражнение 4

Ссылки на изображения разных форматов:
1. [png](https://free-png.ru/wp-content/uploads/2020/07/logo-you-tube-2.png)
2. [jpg](https://timeweb.com/ru/community/article/ff/ff0770833a0026f1b62813408cf5bfb6.jpg)
3. [gif](https://thumbs.gfycat.com/LargeVigilantCardinal-size_restricted.gif)
4. [svg](https://www.flaticon.com/free-icon/svg-file-format-variant_29495#)

Ссылка на логотип YouTube:
[Логотип](https://free-png.ru/wp-content/uploads/2020/07/logo-you-tube-2-1.png)
```

---

### Упражнение 5. Таблицы

### Задачи

1. Создать html страницу как в [упражнении №1](https://www.notion.so/08d9c5797bf3446db67176f15fff23b3) поместить текст из исходных данных

2. Реализовать заголовки столбцам (`tbody` `tr` `td` )

3. Добавить 3 записи в таблицу (`thead` `tr` `td`)

### Исходные данные:

```
Сейчас мы выполняем упражнение 5

Таблица содержит 3 столбца, которые называются (Название товара, Стоимость, Вес) и 3 записи.

Первая запись: Дверь 200р. 6кг
Вторая запись: Телефон 500р. 0.3кг
Первая запись: Утюг 300р. 1кг
```

### Результат работы HTML:

<p align="left">
  <img src="https://vladilen.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F9a0b46ff-66bc-45d4-9906-1bff046800a5%2FUntitled.png?table=block&id=8eb94e2c-32fa-401e-bd97-12e11cccb335&spaceId=4c8a7a76-f839-431a-aed6-1f9189e1c691&width=1690&userId=&cache=v2" width="600px">
</p>

---

### Упражнение 6. Формы

### Задачи

1. Создать html страницу как в [упражнении №1](https://www.notion.so/08d9c5797bf3446db67176f15fff23b3) поместить текст из исходных данных

2. Реализовать форму `from`

3. Добавить поля для ввода имени, почты и даты `input` и подписи к ним с помощью `lable`

4. Добавить поля с типом `radio`

5. Добавить кнопку для отправки данных формы на почту

6. Добавить label для

### Исходные данные:

```
Сейчас мы выполняем упражнение 6

Привет, я риелтор! Свяжитесь со мной по интересующему вас вопросу.

Поле ввода Имя
Поле ввода Почты
Поле ввода для Даты назначения встречи
Поля с типом радио Дом, Квартира, Нежилое помещение
```

### Результат работы HTML:

<p align="left">
  <img src="https://vladilen.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fbbb1c56f-3e42-4d90-a979-721d47656fee%2FUntitled.png?table=block&id=36d108e7-c258-4d15-be54-e34a9fd197b2&spaceId=4c8a7a76-f839-431a-aed6-1f9189e1c691&width=1260&userId=&cache=v2" width="600px">
</p>

---
