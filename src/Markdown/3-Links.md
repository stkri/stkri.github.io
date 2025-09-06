# Verknüpfungen

## Innerhalb eines Dokuments

Du kannst auf ein beliebiges Teil eines Markdown Dokuments verknüpfen,
indem du im Ziel eine Überschrift ID eingibst.

---

```markdown
[Gehe zum nächsten Teil](#innerhalb-einer-website)
```
[Gehe zum nächsten Teil](#innerhalb-einer-website)

---

## Innerhalb einer Webseite

Ähnlich wie vorher kann man auch auf externe Markdown Dokumente verknüpfen.
Dies macht man, indem man die Dateiadresse eingibt.

---

```markdown
[Hier die Einführung zu Markdown](/Markdown/0-Einführung.md)
```
[Hier die Einführung zu Markdown](/Markdown/0-Einführung.md)

---

## Externe Links

Man kann auch externe Webseiten nutzen.

---

```markdown
[Wikipedia](https://en.wikipedia.org/)
```
[Wikipedia](https://en.wikipedia.org/)

---

## Link Titel

Nachdem Ziel kann man in den Klammern mit Gänsefüsschen einen Link Titel schreiben,
welches erscheint, wenn man den Pointer über den Link hält.

---

```markdown
[Wikipedia](https://en.wikipedia.org/ "The free encyclopedia")
```
[Wikipedia](https://en.wikipedia.org/ "The free encyclopedia")

---

## Auto-linking

Man kann auch einen Link erstellen, indem man das Ziel in `< >` schreibt.

---

```markdown
<https://github.com/>
```

<https://github.com/>

---

## Bilder

Wenn man vor einem Link ein Ausrufezeichen setzt, wird es als Bildquelle interpretiert.
Dabei wird der erste Teil des Links als Alt-Text verwendet.

---

```markdown
![Ein Screenshot eines IDEs](/Markdown/img.png)
```
![Ein Screenshot eines IDEs](/Markdown/img.png)