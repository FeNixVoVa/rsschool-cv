1. First name: Vladimir  
Last name: Nazarov
2. Phone number: +7-952-283-99-14  
Discord: FeNix(Вова)#8448  
Mail: FeNixVoVa@gmail.com
3. Objectives: I want to get high-quality knowledge of JavaScript FrontEnd development in order to find a job in the future and start making money on it.
4. Skills: I start learning JavaScript practically from scratch. All I have is knowledge from the school course and desire! Add to this a little more striving and diligence and we will get a quality specialist at the end!
5. Code examples: https://codepen.io/fenixvova/pen/JjrdOXj
```
let inputNumber = prompt('Введите до скольки перечислять простые числа','2');
if ((inputNumber == null) || (inputNumber == undefined)) {
  alert ('Число не введено');
} else if (inputNumber < 2) {
  alert('Принимаются числа больше 1');
} else if (inputNumber == 2) {
  alert('2');
} else {
  let simpleNumbersInResult = 2;
  let numberDivider;
  for (let i = 3; i <= inputNumber; i++) {
    numberDivider = false;
    for (let j = 2; j < Math.sqrt(i); j++) {
      if (i % j == 0) {
        numberDivider = true;
      }
    }
    if (!(numberDivider)) {
      simpleNumbersInResult = (simpleNumbersInResult + ', ' + i);
    }
  } 
  alert(simpleNumbersInResult);
}
```
6. Experience
7. Education
8. English