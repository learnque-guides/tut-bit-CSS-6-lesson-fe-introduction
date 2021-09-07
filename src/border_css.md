# Rėmelio (ang. border) apipavidalinimas

* **border** atributas priima keletas parametru:
  * Rėmelio plotį (1px, 2px ir t.t.).
  * Rėmelio stilių (solid).
  * Rėmialio spalvą (red).
* **border** galima taikyti ne tik visam elementui, bet ir tik tam tikrai daliai (**bordder-top**, **border-bottom**, **border-left**, **border-right**)
* **border-radius** - nusako kaip rėmelio kampai tūri būti užapvalinti (5px, 50%)

```css
.someClass {
    border: 2px solid red;
}

#someID {
    border-top: 2px solid red;
}

div {
    border-radius: 5px;
}
```
