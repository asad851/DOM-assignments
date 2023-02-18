# Task-1
### Before
![before](./ass7.1-before.png)
### After
![Task1 ](./ass7.1-after.png)
```
let leftBoxContent = document.querySelector('.main__languages').children;
for(let i = 2; i<leftBoxContent.length; i++){
     if(i%2!=0)
     {leftBoxContent[i].style.display="none"}
     };
```

# Task-2
### Before
![before](./ass7.2-before.png)
### After
![Task2](./ass7.2-after.png)
```
let inputBox = document.querySelector('.main__form-input');
let submitButton = document.querySelector('.main__form-btn'); 
inputBox.disabled=false; 
submitButton.disabled=false;
inputBox.placeholder="iNeuron"
```
