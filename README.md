// Dog-Years
//This is a simple implementation of JS.
const myAge = 83;
//Setting up a variable for myAge and given it a number.
let earlyYears = 2; 
earlyYears *=10.5;
//This is a variable that will change later.
let laterYears = myAge - 2;
//Multiply the laterYears variable by 4 to calculate the number of dog years accounted for by your later years. Use the multiplication assignment operator to multiply and assign in one step.
laterYears*=4;
console.log(earlyYears);
//Add earlyYears and laterYears together, and store that in a variable named myAgeInDogYears.
const myAgeInDogYears = (earlyYears+laterYears);
let myName ='Joe'.toLowerCase();
console.log(`My name is ${myName}. I am ${myAgeInDogYears} years old in human years which is 10 years old in dog years.`);
