# Igor Appelgants
## Junior Frontend developer
---
### Contacts:
* **Phone**: +7(904)202-19-33
* **Email**: igor.appelgants123@gmail.com
* **Telegram**: @IgorAppelgants 
---
## My skills:
+ Html
+ Css \ Scss \ Sass \ Less
+ JavaScript
+ Gulp
+ React (entry level)
+ VSCode
+ Figma
+ Avacode
---
## About me
Responsibility, punctuality, completion of tasks
on time.

Due to the change of the working sphere of activity, the experience in
site construction is still small. I started studying the IT sphere from the layout
of website pages, now there is a great desire to master
a full-fledged frontend on the react.
I am ready to devote all my free time to mastering the frontend.

---
## Code example:
The sample code is taken from the map on CodeWars

Are they the "same"?

Given two arrays a and b write a function comp(a, b) (orcompSame(a, b)) that checks whether the two arrays have the "same" elements, with the same multiplicities (the multiplicity of a member is the number of times it appears). "Same" means, here, that the elements in b are the elements in a squared, regardless of the order.

```JavaScript
function comp(array1, array2){
  if (array1 === null || array2 === null) {
    return false
  }

  array1.sort(function(a, b) {return a - b})
  array2.sort(function(a, b) {return a - b})

  const arr = array1.map(item => item ** 2)
  
  if (arr.every((item,index) => item == array2[index])) {
    return true 
  } else {
    return false
  }
}
```
---
## My pet projects:
* LightBoard [Isidas.github.io/portfolio/board/](LightBoard "LightBoard")
* Landing page "Mobile recycling collection point"[Isidas.github.io/portfolio/ekologic/](LandinPage "Landing Page")
* Business card website [Isidas.github.io/portfolio/registrator/](BusinesCarWebsite "Business card website")
---
## Education
At the moment I am taking a course on Udemy "JavaScript + React"

---
## Languages:
* Russian — Native
* English — Pre-Intermediate
  