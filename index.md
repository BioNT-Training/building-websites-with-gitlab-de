---
permalink: index.html
site: sandpaper::sandpaper_site
---

:::::::::::::::::::::::::::::::::::::::::  prereq

## Voraussetzungen

Vor der Teilnahme an dieser Lektion sollten die Lernenden idealerweise in der Lage
sein:

1. ein Projekt auf [GitLab][gitlab] / [EMBL GitLab][embl-gitlab] erstellen.
2. Klonen einer lokalen Kopie eines Projekts mit Git, Hinzufügen und Übertragen
  geänderter Dateien und Push/Pull von Änderungen zwischen lokalen und entfernten
  Repositories.
3. Befehle in der Shell ausführen.

Keine der oben genannten Voraussetzungen ist absolut notwendig, um der Lektion zu
folgen. Sie werden jedoch benötigt, um die Entwicklung der Website von Ihrem Laptop
aus effizient zu verwalten und zu testen, wie sie aussieht, bevor Sie offizielle
Versionen erstellen.

Wenn Sie eine der oben aufgeführten Fähigkeiten erlernen möchten, sind die [Software
Carpentry][swc]\-Lektionen über [die Shell][swc-shell] und [Git][swc-git] ein guter
Anfang.

::::::::::::::::::::::::::::::::::::::::::::::::::

Für diejenigen, die bereits mit den Möglichkeiten von Git und einer Online-Plattform wie
GitLab oder GitHub vertraut sind, um Änderungen an flachen Textdateien zu verfolgen und
zu vergleichen und mit anderen an Projekten zusammenzuarbeiten, bieten **GitLab** (und
GitHub) **Pages** eine kostenlose Möglichkeit, Webseiten zu erstellen und zu hosten.
Dieser Ansatz wird häufig für die Dokumentation von Softwareprojekten und für die
Erstellung von Blogs und Websites für Einzelpersonen und Organisationen verwendet, die
bereits mit dem Git-Toolset für ihre anderen Projekte arbeiten. Für diejenigen, die sich
zum ersten Mal mit der Erstellung solcher Websites befassen, kann der Prozess jedoch
verwirrend und einschüchternd sein. Dieses Tutorial soll dies beheben, indem es

1. eine Schritt-für-Schritt-Anleitung zur Erstellung einer Sammlung von Seiten,
2. zeigt mehrere Beispiele, wie man sie zu einer kohärenten Site strukturieren kann,
3. Demonstration der Verwendung verschiedener Frameworks für die Entwicklung von
  Webseiten, von einfachem *HTML* bis *Jekyll* und *Sphinx*.

Der Unterschied zwischen der Entwicklung von GitLab- und GitHub-Seiten wird ebenfalls
kurz besprochen.

::::::::::::::::::::::::::::::::::::::::  callout

## Veraltete Screenshots

In dieser Lektion werden wir Inhalte und Screenshots von [git.embl.de]
([https://git.embl.de/][embl-gitlab]) verwenden und zeigen. Als sich ständig weiterentwickelnde
Plattform fügt GitLab seiner Website ständig neue Funktionen und neue visuelle
Elemente hinzu. **Screenshots** in der Lektion können dann nicht mehr synchron sein,
auf Inhalte verweisen oder diese zeigen, die nicht mehr existieren.

Wenn Sie während der Lektion **Screenshots** finden, die nicht mehr mit dem
übereinstimmen, was Sie in Ihrem Browser sehen, [öffnen Sie bitte ein
Problem](https://git.embl.de/grp-bio-it-workshops/building-websites-with-gitlab/-/issues),
das beschreibt, was Sie sehen und wie es sich vom Inhalt der Lektion unterscheidet.
Fügen Sie bitte so viele Screenshots wie nötig hinzu, um die Diskrepanz zu
verdeutlichen.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::  objectives

## Lernziele

Nach dieser Lektion werden die Lernenden in der Lage sein:

- **erstelle** formatierten Seiteninhalt mit *HTML* oder *Markdown*
- **configure** their project to build and serve pages on GitLab
- **build** eine einfache Seite, um Inhalte in einfachem *HTML* zu hosten
- **erstelle** eine kohärente Site mit mehreren Seiten unter Verwendung des *Jekyll*
  oder *Sphinx* Frameworks
- **anpassen** des Layouts und Stils der Seiten auf ihrer Website

::::::::::::::::::::::::::::::::::::::::::::::::::



[gitlab]: https://gitlab.com/
[embl-gitlab]: https://git.embl.de/



