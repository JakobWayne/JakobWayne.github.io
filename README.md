## Welcome to GitHub Pages

Du kannst den  [Editor von GitHub](https://github.com/JakobWayne/JakobWayne.github.io/edit/master/README.md) benutzen, um den Inhalt Deiner Webseite anzupassen.

Wann immer du etwas änderst, wird [Jekyll](https://jekyllrb.com/) dafür sorgen, dass alle Deine Änderungen sehen werden.

### Markdown

Markdown hilft Dir mit einer einfach zu erlernenden Syntax ohne viel Tipparbeit die verschiedensten Formatierungen zu gestalten:

```markdown
Code für Programme

# Überschrift 1
## Überschrift 2
### Überschrift 3

- Stichpunkt-
- Listen

1. Nummerierte
2. Listen

**Fette-** und _Kursive-_ oder `Code-` Schriften

[Links](url) and ![Bilder](src)
```

Mehr Informationen gibts hier: [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Die Seite benutzt das Theme, das dein Onkel für Dich ausgesucht hat - Du kannst aber jederzeit ein neues aussuchen [repository settings](https://github.com/JakobWayne/JakobWayne.github.io/settings). Der Name wird in den Einstellungen von Jekyll `_config.yml` gespeichert.

### Support or Contact

Irgendwelche Probleme? [documentation](https://help.github.com/categories/github-pages-basics/) oder [contact support](https://github.com/contact) oder natürlich der Onkel Jürgen helfen gern....

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
