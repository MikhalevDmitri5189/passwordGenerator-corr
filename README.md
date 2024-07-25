# Correct password generator

Функция создания правильных паролей, которые будут устойчивы к несанкционированному доступу. Для их создания необходимо указать длину сгенерированного пароля от 8 до 20 символов.
Если вы укажете сгенерировать пароль, состоящий менее чем из 8 или более чем из 20 символов, функция выдает исключение с ошибкой.

## Installing

```npm
npm i correct_password_generator
```

## Usage example

```js
const password = require('correct_password_generator').generatePassword;
console.log(password(10));
// or
const { generatePassword } = require('correct_password_generator');
console.log(generatePassword(10));
```