# Daugiau apie pseudo-class

* Kartais prie elemento norisi pridėti efektą - nedidelę sąveiką su vartotoju arba vaizdinį efektą.
* Pseudoklasės leidžia mums tai padaryti - ribotai aišku :D.
* pseudo-class syntax:

```css {
    selector:pseudo-class {
        property: vlaue;
    }
}
```

Galimos pseudo (ang. pseudo class) klasės yra:
* **:hover** - apibrėžia stilių, kuris turėtų būti taikomas elementui, kai ant jo yra užvedamas žymeklis.
* **:first-child** - apibrėžia elementų sąraše esančio pirmo elemento stilių.
* **:nth-child(2)** - apibrėžia elementų sąraše esančio n eilėje elemento stilių.
* **:link** - stilius, kuris turi būti pritaikytas nuorodai (ant kurios dar nepaspaudėme).
* **:visited** - stilius, kuris turi būti pritaikytas nuorodai (ant kurios jau esame paspaudę)
* **:active** and **:focus** - stiliai, kurie turi būti pritaikyti kai yra fokusas ant elemento.