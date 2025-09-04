# Einführung Markdown

Markdown ist eine Auszeichnungssprache. Was heisst das aber?

> Eine Auszeichnungssprache (englisch markup language, abgekürzt ML) ist eine maschinenlesbare Sprache für die
> Gliederung und Formatierung von Texten und anderen Daten.\
> *[Aus Wikipedia](https://de.wikipedia.org/wiki/Auszeichnungssprache)*

Eine Auszeichnungssprache muss also zwei Zwecke erfüllen.

1. Sie muss Text klar für Menschen gliedern
2. Sie muss Text klar für Maschinen gliedern.

Schauen wir beispielsweise HTML (Hypertext Markup Language), eines der meist benutzten Auszeichnungssprache, an:

```html
<!DOCTYPE html>
<html lang="de">
    <head>
        <title>Titel</title>
        <!-- Weiteres -->
    </head>
    <body>
        <p>Inhalt</p>
    </body>
</html>
```
Man merkt hier aber, dass wir ziemlich vieles geschrieben haben.
Dies ist vorteilhaft, wenn wir wollen, dass die Maschine das möglichst schnell versteht. 
Jedoch brauchen wir dies nicht immer.

Wenn wir unser Beispiel in Markdown umwandeln, sieht es so aus:

```markdown
# Titel

Inhalt
```

Dies ist viel übersichtlicher, vor allem wenn man die Datei direkt anschaut.
In den nächsten Kapiteln wirst du lernen, wie man ein Dokument mit Markdown formatiert.

Übrigens, alle Kapitel auf dieser Webpage sind in Markdown verfasst.
Du kannst die Markdown Dateien jederzeit im 
[GitHub Repo](https://github.com/stkri/stkri.github.io) 
anschauen.

<div class="warning">

Vielleicht erkennst du Markdown von gewissen Messaging Platforms. 
Diese weichen jedoch oft ab vom "echten" Markdown.

Es gibt auch verschiedene "Flavors" von Markdown. 
Diese sind grundsätzlich gleich, haben oft ihre eigenen Features.
Beispielsweise wird diese Warnung nur in mdBook so erstellt werden können.
Wir werden diese Unterschiede **nicht** betrachten.

</div>