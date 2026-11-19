# merspace

> it's more fun when it looks girly

Sammlung kleiner Tools und Skripte rund um merspace. Jedes Tool liegt in
einem eigenen Ordner mit eigener README – hier gibt es nur die Übersicht.

## Tools

| Tool | Was es tut |
| --- | --- |
| – | Noch nichts hier. Das erste Tool bekommt seinen eigenen Ordner unter `tools/` und eine Zeile in dieser Tabelle. |

## Branches („Subrepos“)

Dieses Repo ist das Sammelbecken für den Bereich merspace. Jedes Projekt darin ist ein eigener Branch, quasi ein Subrepo für sich.

> **Regel: Jedes Projekt ist ein eigener Branch, und nichts davon zieht zurück auf `main`.**
> Projekt-Branches werden nicht in `main` gemergt, auch nicht per Pull Request. Weiterentwicklung
> passiert nur im Branch des Projekts (Zwischenschritte gern in Unter-Branches, die dann in den
> Projekt-Branch gehen). `main` ist die Übersicht. Ein neues Projekt bekommt einen neuen Branch
> und hier eine Zeile.

## Struktur

```
merspace/
├── tools/      # eigenständige Tools (je ein Ordner mit eigener README)
└── scripts/    # kleine Einzelskripte ohne eigenen Ordner
```

Neue Skripte kommen direkt in `scripts/`, größere Things bekommen einen
eigenen Ordner unter `tools/` mit einer kurzen README (Zweck, Aufruf,
Abhängigkeiten).
