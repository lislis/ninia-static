## Layouts

In `_layouts` sind die, tadaaa, Layouts zu finden.
`home.html`, `page.html`, `blog.html` und `post.html` 'erben' alle von `default.html`. In default kannst du gut die generelle Struktur anlegen und dann in den anderen nur noch die eigentlichen Unterschiede herausarbeiten.

`index.md` benutzt das home, `about.md` das page, `blog.md` das blog und die beiden Posts das post layout.


## Styles

In `assets/styles` liegen die .scss dateien. `main.scss` ist dabei die Datei, die dann in .css konvertiert wird und in `_layouts/default.html` im `<head>` eingebunden wird.
Weitere scss Dateien kannst du im `_scss` Unterordner anlegen und in `main.scss` importierren.

## JS

JavaScript ist in `assets/js`, wird aber erstmal nicht weiter minified. Diese Datei kannst du von hier auch im head in default.html importieren.


## Themes

Das Standard Theme von vorher gibt's hier https://github.com/jekyll/minima

Das hier ist eine Jekyll-Seite, die ich auch als Prototyp für ein Wordpress theme genutzt habe

https://github.com/lislis/slam-alphas-prototyp
