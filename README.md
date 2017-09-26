# Install

- Clone this repo
- copy dist/ dir to your views/ dir
- Add to your main pug file the lib dist/core.pug Ex: `include bs4-pug/core`

# Navbar

```
+navbar
  +nav-brand
    img(src='/img/icon.png', width='30', height='30', alt='')
  +nav-list
    +nav-item("#","Home","active")
    +nav-item("#","Foo")
    +nav-item("#","Bar")
```

* `+navbar(color, bg)`
    * `color`: navbar-dark, navbar-light, navbar-custom. (Default: navbar-dark)
    * `bg`: bg-white, bg-dark, bg-primary. (Default: bg-dark)
*  `+nav-brand(url)`
    * `url`: Element URL. (Default: "#")
*  `+nav-list()`
*  `+nav-item(url, label, class)`
    * `url`: Element URL. (Default: "#")
    * `label`: Element Label. (Default: "Item")
    * `class`: Item class, ex: active, disabled (Default: none)

