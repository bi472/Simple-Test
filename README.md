# Simple-Test

## 1. Проверка наличия строки в массиве на JavaScript

Для проверки наличия строки в массиве я использую метод `includes` массива. Этот метод возвращает `true`, если элемент найден в массиве, и `false` в противном случае.

```javascript
const array = ["apple", "banana", "cherry"];
const stringToCheck = "banana";

console.log(array.includes(stringToCheck) 
    ? `${stringToCheck} найден в массиве.` 
    : `${stringToCheck} не найден в массиве.`);
```

---

## 2. Получение уникальных имен из SQL-таблицы

Для извлечения уникальных имен из таблицы я использую SQL-запрос с ключевым словом `DISTINCT`. Это ключевое слово гарантирует, что каждое имя будет возвращено только один раз.

```sql
SELECT DISTINCT name FROM table_a;
```

---

## 3. Получение timestamp начала следующего дня на JavaScript

Чтобы определить timestamp начала следующего дня, я создаю объект текущей даты. Затем, используя этот объект, я создаю новый объект даты для начала следующего дня и извлекаю его timestamp.

```javascript
const now = new Date();
const tomorrow = new Date(now.getFullYear(), now.getMonth(), now.getDate() + 1);
const timestamp = tomorrow.getTime();

console.log(`Timestamp начала следующего дня: ${timestamp}`);
```
