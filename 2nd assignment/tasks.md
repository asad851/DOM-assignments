![task1](./task1Output.png)
```

document.querySelector(".accordian-wrapper").querySelectorAll(".accordian")[2].querySelector("p").style.display="block";
document.querySelector(".accordian-wrapper").querySelectorAll(".accordian")[3].querySelector("p").style.display="block"

```

![task2](./task2Output.png)
```
let skills = document.createElement("div"); 
let para = document.createElement("p");
skills.setAttribute("class","accordian"); 
let heading = document.createElement("h3"); 
document.querySelector(".accordian-wrapper").appendChild(skills); 
skills.appendChild(heading); 
skills.appendChild(para);
heading.innerText="Skills"; 
para.innerText="I posses a very good command over the full Stack development technologies like MERN which can be seen in my work present in gitHub "
```
