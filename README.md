# Environmental Data Science Concept Checklist

This concept checklist is insipred by Kyle Bradbury's [Data Science Concept Checklist](https://www.kylebradbury.org/docs/resources/Data-Science-Checklist.pdf).

Compile into PDF file with 

```
pdflatex eds-concept-checklist.tex
```

# How to contribute

If you want to add new or change existing concepts, please follow these simple formatting rules:

## :exclamation: Add a new discipline

Add a `\medskip` after adding the new discipline

```
\discipline{A new Discipline}
\medskip
```

## :exclamation: Add a new topic

Similar as before, but add a `\smallskip` after the new topic

```
\topic{A new topic}
\smallskip
```

## :exclamation: Add a new subtopic and concepts


Adding a subtopic doesn't require any further spacing.

```
\subtopic{New Subtopic}
```

There are two different concepts, *core* (`\cconcept{}`) and a *specialized* (`\sconcept{}`).
Simply add them below the subtopic (or topic, if there is no subtopic).

```
\subtopic{New Subtopic}
\cconcept{First core concept}
\sconcept{First specialized concept}
...
\medskip
```

End a topic or subtopic with a `\bigskip` before a new discipline, with a `\medskip` otherwise.

:orange_book: Happy adding!

