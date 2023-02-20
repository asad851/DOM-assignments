# Task-1
### Before
![before](./ass9.1-before.png)
### After
![after](./ass9.1-after.png)
```
let perfumeName = document.querySelectorAll('.title')[1]; 
perfumeName.style.color="red";
```
# Task-2
### Before
![before](./ass9.2-before.png)
### After
![after](./ass9.2-after.png)
```
let button = document.querySelector('.add-to-cart');
button.addEventListener('mouseenter',()=>{button.style.backgroundColor="red"}); 
button.addEventListener('mouseleave',()=>{button.style.backgroundColor="hsl(158, 36%, 37%)"})
```