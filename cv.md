# Anastasiya Shamal

## Contacts
**E-mail**: aytsan.shamal@gmail.com  
**Phone**: +375 29 680 93 43  
**LinkedIn**: [anastasiyashamal](https://www.linkedin.com/in/anastasiyashamal/)  
**GitHub**: [aytsaN](https://github.com/aytsaN)  
**Skype**: aytsan.shamal  

## Summary
The enthusiastic and detail-oriented Software Engineer is seeking an opportunity to extend the web development knowledge. Having 3 years experience in ServiceNow development using JavaScript. My current position requires less and less coding and logical task solving skills every year. I, on the other hand, desire the opposite of that. My goal is to change my course from IT Service Management to JavaScript developer. Having a positive outlook and am always willing to learn new traits. I work well both independently and as part of a team.

## Skills
- HTML
- CSS
- JS
- Git
- ITIL
- ITSM
- OOP
- Scrum/Agile

## Code Example
 Implement a `spyOn` function which takes any function `func` as a parameter and returns a `spy` for `func`. The returned `spy` must be callable in the same manner as the original `func`.

```
function cache(fun) {
  let memory = {};
  return function(...args) {
    const key = JSON.stringify(args)
    if (!(key in memory)) {
      memory[key] = fun.apply(this, args);
    }
    return memory[key];
  }
}
```

## Education
**Belarusian State University of Informatics and Radioelectronics**  
Economics in Electronic Business  
2014 - 2019

**The Rolling Scopes School**  
2018

**EPAM ServiceNow training**  
2018