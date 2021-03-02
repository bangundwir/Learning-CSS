# **Belajar CSS**

## ***CSS VALUE & UNIT***
**NIlai & Satuan pada CSS**

Contoh :
```css
.selector {
  width: 80%; // 80 disebut value
  height: 500px; // px disebut unit
  font-size: 2em;
  opacity: 0.5;
  transform: rotate(30deg);
  box-shadow: 0 0 10px rgba(0,0,0,.7);
  position: absolute;
  z-index: -9999;
}
```
### CSS value
* **integer** / Bilangan Bulat

**Contoh**
```css
.selector {
  z-index: 1;
  z-index: -9999;
  order: 3;
  grid-column-start: 2;
  grid-row-end: -4
}
```
* **number** / Bilangan pecahan

**Contoh**
```css
.selector {
  opacity: 0.8;
  transform: scale(2.5);
}
```
* **percentage** / "% Merepresentasika sebagian dari nilai tertentu % selalu relative terhadap nilai yang lain"

**Contoh**
```css
.box-besar {
  width: 80%;
  height: 200px;
  background-color: salmon;
}
```
```css
.box-besa .box-kecil {
  width: 50%;
  height: 100px;
  background-color: royalblue;
}
```
* **dimension** / Number yang memiliki satuan di belakangnya
  * Length 
  * angle / sudut
    * deg / degree / derajat
    * rad / radian
    * grad /gradian
    * turn / untuk menentukan berapa putaran
  * time
  * resolution


### **Length - Relative**

|***Relative unit*** | ***Keterangan*** |
:-----:|:-----:|
|% | presentasi ukuran relatif terhadap ukuran elment parent|
|em| relatif terhadap ukuran font yang sedang digunakan |
|rem| relatif terhadap ukuran font "root" / <html>|
|ch| relatife terhadap lebar karakter '0' dari font yang sedang digunakan |
|vh| relatif terhadap tinggi dari viewport|
|vw| relatif terhadap lebar dari viewport|
|vmin| relative terhadap dimensi terkecil sebuah viewport|
|vmax| relative terhadap dimensi terbesar sebuah viewport|