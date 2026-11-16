# goit-js-hw-05

Домашнє завдання 5 з JavaScript: стрілочні функції та перебираючі методи масивів.

- [Репозиторій](https://github.com/MAXGODDYK/goit-js-hw-05)
- [Жива сторінка](https://maxgoddyk.github.io/goit-js-hw-05/)

## Завдання

| Файл           | Функція                                  | Методи                   |
| -------------- | ---------------------------------------- | ------------------------ |
| `js/task-1.js` | `getUserNames(users)`                    | `map()`                  |
| `js/task-2.js` | `getUsersWithFriend(users, friendName)`  | `filter()`, `includes()` |
| `js/task-3.js` | `sortByDescendingFriendCount(users)`     | `toSorted()`             |
| `js/task-4.js` | `getTotalBalanceByGender(users, gender)` | `filter()`, `reduce()`   |

Усі функції зберігають початковий масив без змін. Перевірочні виклики з умови
залишені у відповідних файлах для перевірки ментором.

## Перевірка

Відкрий `index.html` або живу сторінку в сучасному браузері з підтримкою
`Array.prototype.toSorted()` та перейди до DevTools → Console.

Приклади виводять масив імен, два масиви користувачів із зазначеним другом,
порожній масив для відсутнього друга, користувачів за спаданням кількості друзів
та суми балансів: `12053` для `male` і `8863` для `female`.

Перевірити форматування:

```sh
npx prettier --check .
```
