# Task-1
![Task1](./DOM%20P3%20SS-1.png)
```
let logoImg = document.queryselector('.logo');
logoImg.src="https://ineuron.ai/images/ineuron-logo.png"
logoImg.style.width="600px";
let sectionHeading = document.querySelector('.hero').firstElementChild; 
let sectionHeading = document.querySelector('.hero').firstElementChild; 
sectionHeading.style.fontSize="70px"
let rightImg = document.querySelector('top_img');
rightImg.style.position="relative";
rightImg.style.left="47px";

```
# Task-2
![Task2](./DOM%20P3%20SS-2.png)
### For changing the price
```
let price= document.querySelector('.app_price').firstElementChild;
price.innerHTML="$10";
```
### For Social icons
```
let socialIcons = document.querySelector('.footer_social'); 
let linkedIn = document.createElement('div'); 
linkedIn.setAttribute("class","footer_social_ico");
let linkedInIcon = document.createElement('i'); 
linkedInIcon.setAttribute("class","fa-brands fa-linkedin"); 
linkedIn.appendChild(linkedInIcon);
socialIcons.appendChild(linkedIn);
```