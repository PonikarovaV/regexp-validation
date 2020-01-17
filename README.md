# RegExp

Валидация формы с помощью регулярных выражений (учебный проект)

[Демо]: https://ponikarovav.github.io/regexp-validation/

## Требования к полям формы

### Name
- только кириллица;
- первая буква заглавная;
- можно ввести от 2 до 20 символов — это можно задать в атрибутах minlength и maxlength;
- возможна запись двойных имён — например Анна-Мария.

### Email
- только латиница;
- «собака» @ — обязательный символ;
- точка . — тоже обязательный символ.
- цифры, подчерк, тире — разрешённые символы

### Телефон
Шаблон для телефона должен находить номера в таких форматах:

```
+7(925)900-90-90
+7(925) 900-90-90
+7 925-900-90-90
+79259009090
89259009090
```

В номере телефона могут быть пробелы.
