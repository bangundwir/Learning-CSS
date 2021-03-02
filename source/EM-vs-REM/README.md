# em VS rem
 **nilai default  dari browser font adalah = 16px;**
### em (Unit measurement) = Tinggi dari font 
    - em bergantung pada "font size" saat ini
    - em merupakan relative unit yaitu ukuranya bergantung denga font-size element diatasnya(parent) atau didalama seletor yang sama (jika terdapat font-size didalamnya).
    - relative terhadap parent nya
    - cascading => menumpuk
```css
p {
    font-size: 16px;
    border: 0.5em solid black;
}
```
    - menghitug em => nilai 0.5 em adalah 0.5 x 16px = 8px

## rem (root em) = nilai rem hanya terpaku pada font-size di element root yaitu < html > 
    - nilai default 1rem yaitu 16px karena nilaid default html adalah 16px
    - Contoh kasus
  ```css
  html {
      font-size:16px;
  }
  body {
      font-size:0.75rem;
  }
  ```
    - Meghitung rem => nilai 0.75rem adalah 12px. karena 12px / 16px = 0.75rem








### Resources CSS Value & Unit :
- https://www.w3.org/Style/LieBos3e/em​
- https://youtu.be/_-aDOAMmDHI