# Text formatieren in Markdown

## Stilisierter Text

Um normales Text zu schreiben, muss man nichts Besonderes machen.

---

```markdown
Hallo
<!-- Hier ein Kommentar -->
```

Hallo
<!-- Hier ein Kommentar -->

---
\
Wir können den Text fett oder kursiv drucken, unterstreichen, oder durchstreichen.

---

```markdown
*kursiv*
_auch kursiv_
**fett**
__auch fett__
~~durchgestrichen~~
```

*kursiv*
_auch kursiv_
**fett**
__auch fett__
~~durchgestrichen~~

---
\
Vielleicht merkst du, dass keine neue Zeile entsteht.
Man kann eine neue Zeile erstellen,
indem man am Schluss einen `\` einfügen.

___

```markdown
erste Zeile\
neue Zeile

wieder eine neue Zeile
```

erste Zeile\
neue Zeile

wieder eine neue Zeile

---

## Überschriften

Überschriften kann man bis zu sechs Ebenen generieren lassen.

---

```markdown
Ebene 1
===

# Ebene 1 (alternativ)

Ebene 2
---

## Ebene 2 (alternativ)

### Ebene 3

#### Ebene 4

##### Ebene 5

###### Ebene 6
```

Ebene 1
===

# Ebene 1 (alternativ)

Ebene 2
---

## Ebene 2 (alternativ)

### Ebene 3

#### Ebene 4

##### Ebene 5

###### Ebene 6

---
\
Man kann auch horizontale Linien einfügen, um gewisse Teile abzutrennen

---

```markdown
Teil 1

***

Teil 2

---

Teil 3

------------------------------------

Teil 4
```

Teil 1

***

Teil 2

---

Teil 3

------------------------------------

Teil 4

---

# Zitate

Man kann beliebigen Text als Zitat, in dem man vor der Zeile einen `>` schreibt.

---

```markdown
> Ein
>
> langes
> > Noch einer
>
> Zitat

> Ein neues Zitat
```

> Ein
>
> langes
> > Noch einer
>
> Zitat

> Ein neues Zitat

## Sonderzeichen schreiben

Falls du gewisse Sonderzeichen schreiben willst,
ohne dass sie als Markdown Syntax interpretiert werden,
kannst du davor einen `\` schreiben.
Dies funktioniert bei folgenden Zeichen.

- \\
- \`
- \*
- \_
- \{ und \}
- \[ und \]
- \( und \)
- \#
- \+
- \-
- \.
- \!