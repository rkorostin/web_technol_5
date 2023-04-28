# Знакомство с веб-технологиями

xml-парсер: https://jsonformatter.org/xml-formatter

json-парсер: https://jsonformatter.org/json-parser
## JSON и XML
### 1. Проверить XML, правильно ли он составлен, не имеет ли он ошибок, если есть какие-либо недочеты, предоставьте правильный вариант в файле 1.xml:

Неверно
```

<user>

<name>"Иван"</name>

<surname>"Иванов"</surname>

<patronymic>"Иванович"</patronymic>

<age>"30"</age>

<phone>"Москва"</phone>

<birthplace>"+7 926 766 48 48"</birthplace>

</user

```
Верно
```
<user>

<name>"Иван"</name>

<surname>"Иванов"</surname>

<patronymic>"Иванович"</patronymic>

<age>"30"</age>

<phone>"Москва"</phone>

<birthplace>"+7 926 766 48 48"</birthplace>

</user>

```

### 2. Проверить JSON, правильно ли он составлен, не имеет ли он ошибок, если есть какие-либо недочеты, предоставьте правильный вариант в файле 2.json:

Неверно
```

name: "Иван",

surname: "Иванов",

patronymic: "Иванович",

age: "30",

birthplace: "Москва",

phone: +7 926 766 48 48,

```
Верно
```
{
  "name": "Иван",

  "surname": "Иванов",

  "patronymic": "Иванович",

  "age": "30",

  "birthplace": "Москва",

  "phone": "+7 926 766 48 48"
}
```