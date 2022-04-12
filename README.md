# Probuem2
// Работа элемента POP (удоляет элемент с конца мосива)
const myArr = [1, 2, 3]
console.log(myArr)

myArr.pop() // удоление элемента
console.log(myArr)

const removedElement = myArr.pop() //Новая переменная
console.log(myArr)
console.log(removedElement)

// Работа элемента unshift (добовление лементка в начало мосива)
const myArr2 = [1, 2, 3]
console.log(myArr2)

myArr2.unshift(true) // добовление элемента в начало
console.log(myArr2)

const removedElement2 = myArr2.unshift(false) //Новая переменная
console.log(myArr2)
console.log(removedElement2)

// работа элемента shift (удаляет элемент в ночале масива)

const myArr3 = [1, 2, 3]
console.log(myArr3)

myArr3.shift() // добовление элемента в начало
console.log(myArr2)

const removedElement3 = myArr3.shift() //Новая переменная
console.log(myArr3) // орегинальный мосив остается только с отдним элементом
console.log(removedElement3)
