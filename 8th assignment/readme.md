# Task-1
### before
![before](./ass8.1-before.png)
### After
![after](./ass8.1-after.png)
```
let scrollBox = document.getElementsByTagName('aside')[0];
let hrLine = document.createElement('hr');
hrLine.setAttribute("class","hr-line");
scrollBox.appendChild(hrLine);
let heading= document.createElement('h2');
heading.innerText= "This is my custom heading"; 
scrollBox.appendChild(heading);
heading.setAttribute("class","new-head");
scrollBox.style.overflowX="scroll";
```
# Task-2
### before
![before](./ass8.2-before.png)
### After
![after](./ass8.2-after.png)
```
document.body.style.backgroundImage="none"
document.querySelector('.sec-row-p').style.width="283px"
```
# Task-3
### before
![before](./ass8.3-before.png)
### After
![after](./ass8.3-after.png)
```
let toggler = document.querySelector('.navbar-toggler'); 
let collapseMenu = document.querySelector('#navbarTogglerDemo01');
toggler.addEventListener("click",()=>{collapseMenu.style.display = collapseMenu.style.display === 'block' ? 'none' : 'block';})
```