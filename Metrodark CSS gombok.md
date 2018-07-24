# Metrodark CSS gombok

Sötét színezetű metro CSS-gombok.

Ez a kód a honlapon levő összes gomb stílusát átírja, amennyiben az alábbi kódot hozzáadod a **Stílusok táblázata (CSS)** sablonhoz. Amennyiben nem szeretnéd a honlapon levő összes gomb stílusát lecserélni, hanem csak egy adott helyen, akkor a kódot illeszd a kívánt helyre `<style>` és `</style>` tagok közé. 

```css
input[type=reset], input[type=submit], input[type=button] {
  border:1px solid #233423;
  height:30px;
  cursor:pointer;
}

input[type=reset]:hover, input[type=submit]:hover, input[type=button]:hover {
  border:1px solid #233423;
  height:30px;
  cursor:pointer;
  background:#373737;
  color:#fff;
}
```
