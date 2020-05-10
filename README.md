# CCF: Github pages

>Vortrag für CCF (Computer Club Frauenfeld)

Github ist ein kostenloser Online Speicher für Source Code. Eine Webseite besteht auch aus Source Code. Source Code sind reine Textdateien.

Eine Webseite besteht u.a. aus HTML Code. Aber keine Angst, wir müssen nicht HTML schreiben. Stattdessen verwenden wir [Markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf). Dieses Markdown ist eine sehr einfache Sprache und wird automatisch in HTML konvertiert. Doch mehr dazu später.

Hier ein paar Beispiele von solchen Webseiten auf Github:

- <https://clever-geek.github.io/>
- <https://kmlv.github.io/>
- <https://stdm.github.io/>
- auch wenn man es diesen Seiten nicht ansieht, sie sind trotzdem auf Github gespeichert: <https://www.google.com/search?q=site%3A.github.io>
- das was ihr hier lest, ich auch eine solche statische Webseite, welche ich mit Markdown erstellt habe

Wer also Lust hat, innert wenigen Minuten selber ein *statische* Webseite mit Formatierungen, Tabellen und Bildern zu erstellen, kann hier weiter lesen.

>*Statisch* bedeutet, dass wir **keine Eingabemaske** bauen werden. Solche Daten wären dann *dynamische* Daten und müssten in einem Speicher für dynamische Daten gespeichert werden (z.B. in einer Datenbank)

## Account erstellen

Als Erstes müsst ihr einen Github Account erstellen: <https://github.com/>. Das ist kostenlos. Github gehört übrigens Microsoft.

![Anmeldung](./images/signup.png)

## Anmelden

Nach der erfolgreichen Anmeldung könnt ihr euch einloggen. Das sieht dann etwa so aus. Ich habe bereits einige Projekte erstellt, aber bei Euch sieht das etwas anders bzw. leerer aus:

![Github](./images/createrepo.png)

Damit wir nicht zu viel Zeit verlieren, wäre es gut, wenn ihr den Github Login schon vorher erstellen könnt.

Falls Ihr einige (2-3) Bilder verwenden wollt, könnt ihr die auch schon bereit legen. (z.B. auf euren Desktop kopieren)

## Repository erstellen

Oben rechts könnt ihr nun auf das + klicken und "New repository" auswählen. (siehe vorheriges Bild)

Folgendes muss gewählt werden: (das ist wichtig, sonst geht es nicht)

- Repository Name = `<username>.github.io`
- [x] Public
- [x] Initialize this repository with a README

![Neues Repo konfigurieren](./images/confignewrepo.png)

Repository erstellen mit click auf "Create repository"

## Webseite testen

Nach ein paar Minuten sollte die fast leere Webseite bereits erstellt worden sein: `https://<username>.github.io`

Es steht nur das drauf: `<username>.github.io`

> Bitte melden, wenn das nicht läuft.

**Bravo**, wenn es läuft :) Das Schwierigste ist geschafft, nun könnt ihr die Webseite erweitern.

## Readme bearbeiten

Wenn ihr oben rechts auf das (x) klickt, gibt es etwas mehr Platz.

Die Webseite bearbeitet ihr, wenn ihr bei README.md rechts auf den Stift klickt.

![Readme Editor aufrufen](./images/editreadme.png)

## Markdown bearbeiten

Hier ein paar [Markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) Beispiele.

![Readme bearbeiten](./images/editmarkdown.png)

</details>

Die Webseite könnt ihr mit click auf "Commit changes" speichern. Nach ein paar Minuten seht ihr das Resultat auf `https://<username>.github.io` (Browser Refresh oder F5 zum aktualisieren der Webseite)

Bitte übt jetzt mal die verschiedenen Markdown Formatierungen, speichert die Webseite und prüft das Resultat. Wiederholt das Ganze, damit ihr etwas Übung mit Gibhub und Markdown bekommt.

## Bilder

### Bilder hochladen

Bevor ihr Bilder anzeigen könnt, müsst ihr sie auf den Github Server hochladen. Mit "Upload Files" startet ihr in die Upload Funktion:

![Upload starten](./images/uploadstart.png)

Bilder mit der Maus in den mittleren Bereich ziehen:

![Drag/Drop Bilder](./images/dragfile.png)

Speichern mit klick auf "Commit changes".

Den Dateinamen müsst ihr euch merken und dann so in der Webseite eintragen:

``` markdown
![Das ist ein Kommentar falls die Datei fehlt](./dateiname.png)
```

## Tabelle

Wer schafft es, eine kleine Tabelle zu erstellen? Wie das geht, findet ihr in der Markdown Anleitung: <https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf>

## Auf/Zuklappen

Wer schafft es, einen Text auf/zuklappbar anzuzeigen?

<details>
  <summary>Hier ein Beispiel: klickt mich mal an</summary>

... hier kommt das hin was ich verstecken möchte ...

</details>

Leider geht das nicht mit Markdown. Aber mit etwas HTML ist das einfach zu lösen. Einfach diesen Code Schnipsel in euere Webseite kopieren, Texte anpassen. Fertig.

``` html
<details>
  <summary>Hier ein Beispiel: klickt mich mal an</summary>

... hier kommt das hin was ich verstecken möchte ...

</details>
```

Cool! Markdown versteht auch HTML!

## Formatieren von Code

Markdown kann Source code formatieren: cmd, c#, css, html, typescript, javascript, markdown, ...

![Code formatieren](./images/codeformat.png)

Den HTML Codeschnipsel weiter oben (auf/zuklappent von Text) hatte ich so formatiert:

```` html
``` html
<details>
  <summary>Hier ein Beispiel: klickt mich mal an</summary>

... hier kommt das hin was ich verstecken möchte ...

</details>
```
````

## Emojies

GitHub supports emoji!

Damit ich diese Emojies sehe:

- :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat:

Muss ich das eingeben:

- `:+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat:`

Details: <http://www.emoji-cheat-sheet.com>

Es gibt übrigens verschiedene Arten von Markdown. <https://guides.github.com/features/mastering-markdown/>

## Markdown Varianten

Emojies sind "GitHub Flavored Markdown" (Markdown mit Github Geschmack), d.h. Github versteht solche Emojies. Andere Systeme, welche Markdown verarbeiten können, unterstützen das u.U. nicht.
