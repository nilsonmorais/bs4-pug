# Navbar

```
+navbar
  +nav-brand
    img(src='/img/icon.png', width='30', height='30', alt='')
  +nav-list
    +nav-item("#","Home",true)
    +nav-item("#","Foo")
    +nav-item("#","Bar")
```

* `+navbar(color, bg)`
    * `color`: navbar-dark, navbar-light, navbar-custom. (Default: navbar-dark)
    * `bg`: bg-white, bg-dark, bg-primary. (Default: bg-dark)
*  `+nav-brand(url)`
    * `url`: Element URL. (Default: "#")
*  `+nav-list()`
*  `+nav-item(url, label, active)`
    * `url`: Element URL. (Default: "#")
    * `label`: Element Label. (Default: "Item")
    * `active`: If element is active. (Default: false)

