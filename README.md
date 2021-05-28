## Тестове завдання для Yalantis React.js School (online)

##### `npm i`

##### `npm start`

#### `gh-pages`: https://denysoleksiienko.github.io/yalantis-react-app/

##### Tech Stack: HTML, CSS(SCSS), React (Reach Hooks), Axios

#### Задача:

GET: `https://yalantis-react-school-api.yalantis.com/api/task0/users` повертає масив юзерів. У кожного юзера є наступні поля: id, firstName, lastName, dob (дата народження).

Реалізувати:

1. загрузку юзерів
2. відображення списку місяців
3. підсвітити місяці в залежності від кількості людей, які народилися в цьому місяці.
4. при наведенні на обраний місяць — відобразити список людей, які народилися в цьому місяці.

Умова за кількістю людей, за яким підсвічувати місяці:
[0-2] - сірий
[3-6] - синій
[7-10] - зелений
[11+] - червоний
