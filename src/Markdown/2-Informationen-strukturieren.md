# Informationen klar strukturieren.

## Listen

### Unnummeriert

Man kann eine unnummerierte Liste erstellen, indem man vor den Punkten einen `-` schreibt

---

```markdown
- Hallo
    - Hallo
- Hallo
- Hallo
```

- Hallo
- - Hallo
- Hallo
- Hallo

---

### Nummeriert

Man kann eine nummerierte Liste, indem man vor jedem Punkt eine Zahl hinzufügt.

---

```markdown
1. Punkt 1
    1. Punk 1.1
2. Punkt 2
58. Punkt 3
<!-- Beachte, dass das letzte nicht als 58 ausgegeben wird-->
```

1. Punkt 1
    1. Punk 1.1
2. Punkt 2
58. Punkt 3

---

## Tabellen

Man kann eine Tabelle erstellen, in dem man diese mit `|` darstellt.

---

```markdown
| Zeile 1 | Zeile 2 |
|---------|---------|
| Reihe 1 | Reihe 1 |
| usw.    | usw.    |
```

| Zeile 1 | Zeile 2 |
|---------|---------|
| Reihe 1 | Reihe 1 |
| usw.    | usw.    |

## Code

Um innerhalb einer Zeile Code darzustellen, nutzt man die folgende Syntax.

---

```markdown
Wir werden danach ein Beispiel in `rust` sehen.
```

Wir werden danach ein Beispiel in `rust` sehen.

---
\
Um einen Codeblock zu erstellen, nutzt man die folgende Syntax.

---

````markdown
```rust
fn main() {
    println!("Hello, World!");
}
```
````

```rust
fn main() {
    println!("Hello, World!");
}
```