![task](./DOM%20P1%20SS.png)
for barbarian specs color change
```
let barbarian = document.getElementsByClassName("clash-card__unit-stats clash-card__unit-stats--barbarian clearfix")[0];
barbarian.style.backgroundColor="rgb(232, 163, 81)";
barbarian.style.color="white";
barbarian.lastElementChild.style.color="white";
```

for char2 
```
document.getElementsByClassName("clash-card archer")[0].firstElementChild.nextElementSibling.nextElementSibling.innerText="The Archer";
let char2=document.getElementsByClassName("clash-card__unit-stats clash-card__unit-stats--archer clearfix")[0];
char2.style.backgroundColor="#d66088";
char2.style.color="white";
char2.style.color="white";
```

for giant 
```
let giant = document.getElementsByClassName("clash-card__unit-stats clash-card__unit-stats--giant clearfix")[0];
giant.style.backgroundColor="#d99a52";
giant.style.color="white";
giant.lastElementChild.style.color="white";
```
for Goblin
```
document.getElementsByClassName("clash-card goblin")[0].firstElementChild.nextElementSibling.nextElementSibling.innerText="The Goblin";
let goblin =  document.getElementsByClassName("clash-card__unit-stats clash-card__unit-stats--goblin clearfix")[0];
giant.style.backgroundColor="#95c156";
giant.style.color="white";
giant.lastElementChild.style.color="white";
````
for The Wizard
```
let wizard = document.getElementsByClassName("clash-card__unit-stats clash-card__unit-stats--wizard clearfix")[0];
wizard.style.backgroundColor="#76abd9";
wizard.style.color="white";
wizard.lastElementChild.style.color="white";
```
