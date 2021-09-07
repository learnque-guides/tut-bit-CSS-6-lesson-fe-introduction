# CSS stiliaus atributai (properties)

Anksčiau pateiktuose pavyzdžiuose jau matėme kai kurias CSS stiliaus savybes/atributus (pvz., color ar border), todėl pažiūrėkime, kokias kitas savybes galėtume pakeisti!

* **color** ir **background-color** naudojami teksto arba fono spalvai pakeisti o jų reiksmšmės gali buti spalvu pavadinimai (pvz., green, red, magenta, ...) arba HEX RGB reikšmes (pvz., #000, #0FF9BB, ...).
* **background-image** - elemento fonui užpildyti naudojant paveikslą (galima naudoti tiek rastrinį, tiek vektorinį). [Nuoroda](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_background-image)
* **width** ir **height** priima tokias vertes kaip 10px, 100% ar šiek tiek sudėtingesnės (pvz., 2em, 10rem, ...). Apie tai kuom skiriasi dydžio vientai (ang. measurements units) pagalbėsime vėliau.

---

```css
div {
    color: red;
    background-color: #000;
    background-image: url("paper.gif");
    width: 100%;
    height: 150px;
}
```
