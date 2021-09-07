# clear ir clearfix

`clear` CSS savybė nusako ar elementas turi būti pajudintas žemiau (cleared) kitų elementų, kurie yra prieš jį. `clear` yra pritaikomas tiek floating (pritaikyta float savybė) ir non-floating (ne pritaikyta float savybė) elementams.

Kad būtų aiškiau suprasti, įsivaizduokite, kad turime tokį html fragmentą:

```css
.example-container {
    background-color: #eee;
    border: .75em solid;
    padding: .75em;
    text-align: left;
    line-height: normal;
}

.floated-left {
    border: solid 10px #ffc129;
    background-color: rgba(255,244,219,.6);
    padding: 1em;
    float: left;
}

.floated-right {
    border: solid 10px #ffc129;
    background-color: rgba(255,244,219,.6);
    padding: 1em;
    float: right;
    height: 150px;
}
```

```html
<div class="example-container">
    <div class="floated-left">Left</div>
    <div class="floated-right">Right</div>
    <div id="example-element">As much mud in the streets as if the waters had but newly retired from the face of the earth, and it would not be wonderful to meet a Megalosaurus, forty feet long or so, waddling like an elephantine lizard up Holborn Hill.</div>
</div>
```

Panagrinėkime kaip kinta floating (kuriems pritaikyta `float` savybė) elementų išsidėstymas priklausomai nuo `clear`

---

<style>
    .interactive {
        background-color: #f4f4f4;
        border: 1px solid #d5d5d5;
        color: #1b1b1b;
        padding: 10px;
        width: 100%;
    }
</style>
<iframe class="interactive" height="390" src="https://interactive-examples.mdn.mozilla.net/pages/css/clear.html" title="MDN Web Docs Interactive Example" loading="lazy">
</iframe>

