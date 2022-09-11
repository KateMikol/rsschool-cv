# Ekaterina Gornovskaya

## Student at RS School

## Contact information

* City: Minsk
* Phone: +375 33 613-63-68
* E-mail: gornovskayakt@gmail.com
* Telegram: @katemikol
* Discord: KateMikol

## Breefly about me

I'm working as a power engineer at the design institute. I love learning new. My strengts are in fast learning and teamwork skills. 
I want to create new and useful things and it is the main reason why I'm here. 

## Skills 
* VS Code
* HTML5? CSS3 (Basic)
* JavaScript (Basic)
* Python (Basic)

## Code example
**function** maxTriSum(numbers){
  let sum = 0;
  let count =0;
  numbers.sort(function(a,b) {return b-a});
  **for** (let i = 0; i < numbers.length; i++){
    **if** (numbers[i] != numbers[i+1] && count < 3){
      sum += numbers[i];
      count += 1;
      } **else**{
      sum += 0;
    }
  }
  **return** sum;
}