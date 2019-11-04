# `WHAT I LEARNED IN WEEK 8`



### `Functional Programming`

* Some examples include:
```
function returnFromFunc(func) {
  return func()
}

function modifyString(str,func) {
  return func(str)
}

function modifyNumber(num,func) {
  return func(num)
}

function modifyAnything(value,func) {
  return func(value)
}
```
---

### `Weather Project`
I loved this project! It helped me to learn functional programing more. I like to use our old project and improve it. 

---
### `Funculate`

We used our calculate function to use other functions. This project was little bit confusing at first but then it was more clear.

```
if (isAddition) {
    return performCalculation(add, num1 , num2);
  } else if (isSubtraction) {
    return performCalculation(subtract, num1 , num2)
  } else if (isMultiplication) {
    return performCalculation(multiply, num1 , num2)
  } else if (isDivision) {
    return performCalculation(divide, num1 , num2)
  } else if (isModulus) {
    return performCalculation(modulus, num1 , num2)
  } else {
    return `Sorry, that's not a mathematical operation!`
  }

```
---

### `Domosaur`

I think this project was the most helpful in terms of teaching the concept. It was more clear about why we use functional programing. I like that we worked with partners. One of the most helpful part of the project was the following:
```
function changeTo200(event){
    event.target.style.width = '200px';

}
document.querySelector('#biggify').addEventListener('mouseenter', changeTo200)

function changeBack(event){
    event.target.style.width = '162px';

}
document.querySelector('#biggify').addEventListener('mouseout', changeBack)
```
---
### `Extinction-Event`

This was very confusing at first. Then I figured out most of it. I am looking forward to going over in class!

```

const newUl = document.querySelectorAll('.app ol li')
function lineThru(event){
event.target.style.textDecoration = 'line-through'
}

function eventListenerLoop () {
    for (let i=0;i<newUl.length;i++) {
    newUl[i].addEventListener('click',lineThru);
}
}

eventListenerLoop()

const newUlLi = document.querySelectorAll('.app ul li')
function changeOpacity(event){
event.target.style.opacity ='0'
}

function eventListenerLoop2 () {
    for (let i=0;i<newUlLi.length;i++) {
    newUlLi[i].addEventListener('click', changeOpacity);
}
}

eventListenerLoop2()
```
---
### `Midterm`
I hope I didn't fail.. Looking forward to see my grade.
---