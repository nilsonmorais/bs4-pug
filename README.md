# Install

- Clone this repo
- copy `dist/` dir to your `views/` dir
- Add to your main pug the file `dist/core.pug` Ex: `include bs4-pug/core`

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

* `+navbar(class)`
    * `class`: navbar-dark, navbar-light, navbar-custom. (Default: navbar-dark bg-dark)
*  `+nav-brand(url)`
    * `url`: Element URL. (Default: "#")
*  `+nav-list()`
*  `+nav-item(url, label, class)`
    * `url`: Element URL. (Default: "#")
    * `label`: Element Label. (Default: "Item")
    * `class`: Item class, ex: active, disabled (Default: none)

# Cards

```
+card
  +card-img("/img/img.png", "Alt text")
  +card-title("Title")
  +card-subtitle("SubTitle")
  +card-body
    | Foo
  +card-list
    +card-list-item 
        | Item 1
    +card-list-item 
        | Item 2
    +card-list-item 
        | Item 3
  +card-body
    +card-text
        | Some text

+card
  +card-header
    | Title
  +card-body
    | Foo

```

* `+card()`
*  `+card-img(url,alt)`
    * `url`: Element URL. (Default: "#")
    * `alt`: Element alt property. (Default: "")
*  `+card-title(text)`
    * `text`: Text label (Default: "")
*  `+card-subtitle(text)`
    * `text`: Text label (Default: "")
*  `+card-body()`
*  `+card-list()`
*  `+card-list-item()`
*  `+card-text()`
*  `+card-header()`

