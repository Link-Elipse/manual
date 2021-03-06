# Contributing

This project is an ongoing work, and we need your help. li3 users _new_ and _old_ are welcome and encouraged to join in the fun. If you've struggled with something, help us record and share the solution so others can find the way more easily. There are many ways you can help:

 * Code examples to enrich current documentation
 * Do lists or tables to help explain concepts
 * Rough notes that describe an oft-used process
 * Corrections (typos, inaccuracies, etc.)
 * Translations

If you'd like to help, simply [fork the project on GitHub](https://github.com/UnionOfRAD/manual), [open a new issue](https://github.com/UnionOfRAD/manual/issues), or get in contact with one of the core team members. You can give us a shout in channel #li3 on server Freenode, or send an email to anderson.johnd at gmail dot com.

## Markup

We're using GitHub markdown to render the final documents. 

### Notes

You add notes using the following markup:

```html
<div class="note note-info">
	Informational note here.
</div>
```

There are 3 classes of notes _caution_ (class is `note-caution`), _informational_ (`note-info`) 
and _hints/tips_ (`note-hint`). Any code inside the divs will need to be marked up manually using
`<code></code>` tags.

### Versions

There will be no separate manuals for minor versions. Instead features available only 
in since certain versions are documented as follows:

```html
<div class="note note-version">This feature is available with version 1.1.</div>
```

### Code

Use tabs to indent the code inside fenced code blocks. This allows us to adjust the spacing when rendering and highlighting the code.

Language hints may be used for snippets - where its hard to detect the language automatically.


