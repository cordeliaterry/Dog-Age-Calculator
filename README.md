# DogAgeCalculator
Converting age in human years to dog years using JavaScript

//my age
const myAge = 18;
//first two years of life
let earlyYears = 2; 
earlyYears *= 10.5;
//time changes after 2 years so subtracting those years here
let laterYears = myAge - 2;
//multiplyng later years by 4
laterYears *= 4; 
//age in dog years
let myAgeInDogYears = earlyYears + laterYears;
//name in all lowercase
let myName = 'Sammy'.toLowerCase(); 
console.log(`My name is ${myName}. I am ${myAge} years old in human years which is ${myAgeInDogYears} years old in dog years.`)
