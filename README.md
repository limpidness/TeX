# README
README-Datei des Repository "TeX". 

## Inhalte
Aktuell besteht das Repository aus zwei Paketen und einem Beispiel. Weitere Beispiele und Dateien (beispielsweise Vorlagen) sind geplant.

### Pakete
* Das Paket `basis.sty` lädt eine Reihe von Paketen, die allgemein erforderlich sind, etwa für die Zeichencodierung und Sprachpakete.
* Das Paket `mathe.sty` enthält nützliche Makros für mathematische Texte. Die `ams`-Pakete (`amsmath` etc.) müssen vorher geladen werden; sie werden in `basis.sty` geladen.

## Verwendung
Die Pakete `basis.sty` und `mathe.sty` können in das TeX-Projektverzeichnis kopiert werden, in dem sie benötigt werden.

Eine bessere Alternative dazu ist die Verwendung jener Verzeichnisse, in denen die verwendete TeX-Distribution automatisch nach Paketen sucht. Bei Verwendung von `TeX Live` unter Linux ist das etwa das Verzeichnis `~/texmf/tex/latex/local/`.
