### Install
```sh
npm i pass-gen --save
```

| Available options | Explication |
| ------ | ------ |
| all | Generate a password with all characters |
|num | Generate a password with only numbers | 
| letter | Generate a password with only letters
| nosymbols | Generate a password only with letters & numbers

### Usage
```js
const gen = require("pass-gen")

let length = 10

console.log(gen.all(length))
```