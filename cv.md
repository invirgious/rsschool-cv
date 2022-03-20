# Ksenia Fedisheva

### Junior Frontend Developer

## Contact Information
* __Location:__ Russia, Rostov-on-Don  
* __Phone:__ 8 (928) 155 - 77 - 93
* __E-mail:__ <tubiksu@gmail.com>
* __Telegram:__ @farfelue
* __GitHub:__ invirgious 

## About Me
My path in programming began with the fact that I decided to go to university majoring in IT-systems and technologies. During my studies, I spent a long time looking for exactly the IT direction that I would like to do with pleasure every day. After years of searching and trying, I realized that the very direction is frontend development. I really like the field of programming in general, so in the future I plan to link my life with development, in particular with the development of the client side of websites.

## Skills and Experiences

* HTML5 / CSS3
* JavaScipt (basic)
* Adobe:
  *  Photoshop
  *  Illustrator
  *  XD
* Figma
* Git / GitHub
  
## Code Example

__Count of positives / sum of negatives__
Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.

If the input is an empty array or is null, return an empty array.

__Solution__

```javascript
function countPositivesSumNegatives(input) {
  let array = [0,0];
  
  if(input == null || input.length === 0){
    return [];
  }

  for(let i = 0; i < input.length; i++){
    if(input[i] > 0){
        array[0] += 1;
  }
  else {
    array[1] += input[i];
  }

  }
    return array;
  }
```
## Education

2018 - 2022
* __Bachelores Degree__<br>
  __Don State Technical University__ - IT-systems and technologies

## Education Courses

* Modern JavaScript Tutorial on [learn.javascript.ru](https://learn.javascript.ru/) (in progress)
* JavaScript Algorithms and Data Structures on [freeCodeCamp.org](https://www.freecodecamp.org/) (in progress)
* The Complete JavaScript + React Course - From Zero to Result on [Udemy.com](https://www.udemy.com/) (in progress)

## Languages
* English - B1 (intermediate)
* Russian - Native