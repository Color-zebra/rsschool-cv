# Dmitriy Romanenkov
### RS School student (front-end), from Bryansk.

<br/>
<br/>
<br/>

## Contacts
<br/>

![DISCORD](https://img.shields.io/badge/-Discord-000000?style=for-the-badge&logo=discord&logoWidth=49)
Дмитрий(@Color-zebra)

![EMAIL](https://img.shields.io/badge/-EMail-000000?style=for-the-badge&logo=mail.ru&logoWidth=69) Dimon32rus@mail.ru

![TELEGRAM](https://img.shields.io/badge/-Telegram-000000?style=for-the-badge&logo=telegram&logoWidth=40) 
https://t.me/color_zebra

<br/>
<br/>
<br/>

## Skills
<br/>

![HTML5](https://img.shields.io/badge/-HTML5-000000?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS-000000?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/-javascript-000000?style=for-the-badge&logo=javascript)
![GIT](https://img.shields.io/badge/-GIT-000000?style=for-the-badge&logo=git)
![SCSS](https://img.shields.io/badge/-scss/sass-000000?style=for-the-badge&logo=sass)

<br/>
<br/>
<br/>

## Code example
<br/>

The function receives the color in RGB format. Valid decimal values for RGB: 0-255. Any values outside this range should be rounded to the nearest valid value. The function should return the color in HEX format. 
``` JavaScript
function rgb(r, g, b){
  let arg = Array.from(arguments).map(function(item) {
    if (item > 255) {item = 255};
    if (item < 0) {item = 0};
    return item;
  });
  return (('0' + arg[0].toString(16)).slice(-2) + ('0' + arg[1].toString(16)).slice(-2) + ('0' + arg[2].toString(16)).slice(-2)).toUpperCase();
}; 
```
