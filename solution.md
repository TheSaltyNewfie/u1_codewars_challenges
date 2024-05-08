## Return Negative

```js
function makeNegative(num) {
  if (num > 0) {
    return -num;
  }
  return num;
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let pos = 0
  
  arr.forEach(num =>{
    if(num>0) {
      pos += num
    }
  })
  
  return pos
}
```

## Function 2

```js
function square(num){
  return num * num;
}
```

## Sum Arrays

```js
function sum (numbers) {
  let x = 0
  
  numbers.forEach(num => {
    x += num
  })
  
  return x
};
```

## Reversed Strings

```js
function solution(str){
  return str.split('').reduce((reversed, char) => char + reversed, '')
}
```
