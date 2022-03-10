# Stanislav Vasiurin
### Junior Frontend Developer
 
---
 
### Contact information:
 
**Phone:** +375 29 7106905<br>
**E-mail:** vasyrin1312@gmail.com<br>
**Telegram:** @arxons<br>
 
---

### Some words about Myself:
 
When some people are asked to say a few words about themselves, they often get confused and don't know what to answer.<br>
But that's not me. About myself I can say that my main goal is to learn and improve in the field of front-end development and everything connected with it.<br> 
I would like to mention my strengths. Such as responsibility and punctuality. These are not empty words.<br>
Once, when I was doing another project the customer tightened the deadline and I had to spend the whole night completing endless lines of code instead of just going to bed.<br>
I had never worked for any company before. I used to do orders from people I knew. Or did something for myself.<br>
 
---

### My Skills:
 
- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code,
- Adobe Photoshop, Adobe Premier Pro, Adobe Audition
 
---

**Find the odd int kata:**
*Given an array of integers, find the one that appears an odd number of times.There will always be only one integer that appears an odd number of times.*
 
```javascript
function findOdd(A) {
let objRes = {};
for (let i = 0; i < A.length; i++) {
    let n = A[i];
    if (objRes[n] != undefined) {
        objRes[n]++;
    } else objRes[n] = 1;
}
let newArr = [];
for (let key in objRes) {
    if (objRes[key] % 2 !== 0) {
        newArr.push(key);
    }
}
return Math.max(newArr);
}
```
---

### Courses:
 
- Basic HTML and CSS, JS algorithms on [freecodecamp](https://www.freecodecamp.org) (completed)<br>
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
 
---
 
### Languages:
 
- English \- B1
- Russian \- Native
