# Informatik-12.1

## Inhaltsverzeichnis

[Unser Projekt](#1)

[Blog](#2)

[Fazit](#3)

[Finale Links](#4)

[Projektseite als PPP](#5)

### <a name="1"></a>Unser Projekt
Das Projekt Kladde ist eine App für Androidgeräte, in der man sich Einkaufslisten einfach und nach Laden organisiert erstellen kann. Zudem hat man Zugriff auf Themenbezogenen Websites wie Amazon. Die App wurde von Vanessa Vaino, Farhat Arfendi und Antonia Köhler erstellt.
Der Name basiert einfach darauf, dass man Einkaufslisten meist auf Schmierzetteln schreibt, oder anders: Auf der Kladde.
Die Idee für die App stammt aus unserem eigenen Alltag. Das Ziel war es für uns eine App zu erstellen, die nützlich ist (also kein Spiel) und im Alltag anwendbar ist. Aus einem Problem, dass man immer die Einkaufszettel verliert und diese unübersichtlich sind, entstand unsere Idee. Zudem muss unsere App im Rahmen des Möglichen beim Programmieren liegen, da niemand aus unserer Gruppe anfangs Erfahrung in diesem Bereich hatte.
Die Zielgruppe der App sind Boomer, welchen die einfache Handhabung der App zuvorkommt und eine Digitalisierung des Alltags erleichtert. Das Design haben wir zurückhaltend, neutral, aber dennoch ästhetisch ansprechend in Pastell-Farben gewählt.

### <a name="2"></a>Blog 
## 03-08-2021

Wir haben uns einen GitHub Account angelegt und einen ersten Überblick über die Möglichkeiten, die wir haben, gemacht. Dabei haben wir uns erst einmal allgemein über das Thema Programmieren informiert, da dieses komplettes Neuland für Vanessa und Antonia war.

## 04-08-2021

Heute haben wir uns weiter mit GitHub vertraut gemacht und das Projekt mit den Accounts der Teammitglieder verknüpft. Zudem haben wir unser erstes Update bei GitHub geschrieben. Danach haben wir Applab ausprobiert und uns daran versucht, eine To-Do Liste zu programmieren. Dabei mussten wir aber feststellen, dass das Programm dafür nicht ganz so gut geeignet ist. Wir haben uns vorgenommen, uns zuhause weiter über mögliche Programme und Projekte zu informieren.

## 10-08-2021

Nach einigen Recherchen, sind wir uns klarer darüber geworden, was im Rahmen des Möglichen als Projekt für uns Programmier-Neulinge liegt. Auch haben wir uns mit Herrn Buhl darüber ausgetauscht und sind dank ihm auf das Programm AppInventor gekommen. Mit diesem haben wir uns anschließend vertraut gemacht und angefangen eine Einkaufsliste, bei der man Listen anlegen kann und diese nach Supermärkten sortiert, zu programieren. 
Aufbau:

Startscreen --> Wähle Einkauf

Es öffnet sich Screen 2 --> Wähle Art von Laden 

Es öffnet sich leere Einkaufsliste zum selbst ausfüllen und abhaken

Leider kann man in der Webversion nicht testen, ob das aktuelle Programm läuft, weshalb wir bis nächste Stunde warten müssen, um unsere anfänglichen Versuche zu testen. Denn die App läuft nur auf einem Android-Gerät, welches wir heute nicht dabei haben.

## 11-08-2021
Die Stunde ist ausgefallen.

## 18-08-2021
Die ganze Klasse ist durch die Klassenfahrt verhindert gewesen.

## 19-08-2021
Die ganze Klasse ist hier ebenfalls durch die Klassenfahrt verhindert.

## 24-08-2021
Vanessa und Antonia waren beide krank.

## 25-08-2021
Farhat hat sich unserer Gruppe angeschlossen. Wir haben die App das erste Mal auf einem Android-Gerät testen können und weiter daran gearbeitet. Zuwider unserer Erwartungen haben unsere ersten Programmierversuche sogar funktioniert und wir haben uns sehr über diesen unerwarteten, ersten Erfolg gefreut. Folgendes hat schon geklappt: Von Screen 1 zu Screen 2 zu Screen 3 wechseln (indem man einen Knopf drückt). Textfelder zu erstellen, in die man etwas frei reinschreiben kann und ein Button, der, wenn man ihn betätigt, die Farbe der Textfelder wechseln lässt (für eine Einkaufsliste, zum Abchecken). Auch Dinge, die wir frei ausprobiert haben und möglicherweise später noch von uns genutzt werden, wie zum Beispiel ein Soundeffekt beim Betätigen der Knöpfe, haben wir zwar wieder entfernt, aber haben auch funktioniert. Nachdem die ersten Programmierschritte gelungen sind, schauen wir uns als Nächstes das Layout an.

<p align="center">
  <img width="300" src="https://user-images.githubusercontent.com/88386173/137918798-cf7f6e69-57ef-4c46-bc83-063c1a1e7efb.PNG">
</p>

Auf diesem Bild sieht man eine unserer ersten Screens der App, auf der man eine Art von Supermarkt aussuchen kann. Noch besteht der Screen nur aus Buttons, das Layout wird aber noch verändert.

![code 2](https://user-images.githubusercontent.com/88386173/145066914-9523b9a8-aeba-4de7-963c-bea1d05bdb20.PNG)

Auf diesem Bild sieht man die ersten Programmierversuche unserer Gruppe. Dieses Programm ist dafür da, mit der Hilfe von Knöpfen durch die Seiten zu navigieren.

![bild3](https://user-images.githubusercontent.com/88386173/145066964-be6b2f99-a3cf-4c53-837e-903a0f04b52e.PNG)

Dies ist unser erster Entwurf, wie eine (Laden-spezifische) Einkaufsliste aussehen könnte. Allerdings ist ein einzelner Knopf für jede Textbox und auch viele Textboxen sehr ineffizient, weshalb wir diese Funktion später abgeändert haben.

![altercode4](https://user-images.githubusercontent.com/88386173/145067012-fdcf4e75-8f09-4bdb-84e2-0f39619b28ba.PNG)

Dies ist der Code, mit welchem man eine Farbe der Textbox ändern kann. Diese Funktion ist dafür gedacht, dass man Teile der Liste "abhaken" kann. (Nachtrag: Die Funktion haben wir im Nachhinein auch gelöscht und anders gelöst).

## 31.08.2021
Farhat war heute krank. Wir haben eine Möglichkeit gefunden, unseren Code weniger aufwendig und kürzer zu halten, mit der wir auch noch Buttons in der App einsparen. Das bedeutet, dass ein Knopf mehrere Funktionen übernehmen kann, wenn man ihn öfters drückt. In diesem Beispiel hatten wir einen Knopf, der die Textbox einfärbt und einen, welcher sie wieder normal färbt. Diese haben wir zusammen gelegt. (Nachtrag: Auch diese Codes findet man in der finalen Version nicht mehr, da sie durch noch effizientere Codes ersetzt wurden). Auch haben wir uns heute auf das Layout der App konzentriert und unsere Codes, sowohl wie die grafischen Objekte sortiert, in den Farben stimmiger gestaltet und einige einfache, aber wichtige Knöpfe (wie z.B. "zurück") auf jeder Seite erstellt. Nächste Stunde richten wir alle Listen ein, da wir momentan nur an einer einzigen Liste die Codes testen. Zusätzlich versuchen wir eine Uhr auf dem Startbildschirm einzublenden.

![altercode5](https://user-images.githubusercontent.com/88386173/145067046-15cd676c-2500-41f9-83ca-8f47f2bc4148.png)

![änderung](https://user-images.githubusercontent.com/88386321/138893230-d19bcf3b-7bd4-4ba5-9c82-52e8f6610c27.PNG)

---


Hier sieht man einen Teil, des alten (oben) und den neuen (unten) Code im Vergleich. Wie man sieht wurden sie zusammengelegt und dadurch einige Buttons eingespart, was die Bedienoberfläche einfacher und übersichtlicher macht. Denn beim alten Code, braucht man die doppelte Anzahl an Knöpfen, um die Textkästen wieder zurückzufärben. Dieser Unterschied ist auch unten nochmal auf dem Handy gezeigt, der obere Teil wäre die alte Ansicht und der untere ist die Neue.

![grafik](https://user-images.githubusercontent.com/88386173/145066023-7b0235e6-2efc-4d26-a5a8-e952f9a1fea6.png)

![bild3](https://user-images.githubusercontent.com/88386173/145067370-2d828d50-3167-4ab5-b107-3797a3e28f68.PNG)

## 01.09.2021
Heute haben wir Farhat die Fortschritte in der App gezeigt und gemeinsam eine To-Do-Liste erstellt, zu dem Thema, was noch erledigt werden muss. Danach haben wir Hintergrundbilder für alle einzelnen Seiten herausgesucht und auch teils schon reingestellt. Auch den Datum-Button haben wir teilweise fertig programmiert und werden ihm Dienstag den letzten Finish geben. Zusätzlich haben wir nach einer Möglichkeit gesucht, die Texte in den Textboxen zu speichern, sind aber bislang zu keiner zufriedenstellenden Lösung gekommen. 

```diff 
- Unsere To-Do-Liste:

-Speicher-Button erstellen, um Objekte in der Liste zu speichern

-Delete-Button erstellen, um eine Liste zu leeren

-New-Item-Button erstellen, um neue Items zur Liste hinzuzufügen

-Uhrzeit und Datum auf der ersten Seite anzeigen

-Hintergrundbilder auf allen Seiten

-Soundeffect beim Klicken auf Buttons einfügen
```


## 07.09.2021 
Antonia ist heute krank. Unser Computer hatte ein Fehler und da Antonia nicht da war, konnten wir uns Anfangs nicht in App Inventor einloggen. Deshalb haben wir auf Pexels Hintergrundbilder für unsere App herausgesucht. Nachdem wir verschiedene Bilder gesammelt haben, haben wir für Farhat einen GitHub Account erstellt. Zum Ende hin haben wir es dann doch noch geschafft in App Inventor hereinzukommen. Also haben wir am Ende die herausgesuchten Bilder eingefügt.  

![ladenwählen](https://user-images.githubusercontent.com/88386321/138900145-1739c5c0-5f4d-4422-8ed5-4d7dfbc49fa4.png)

Hier ein Beispiel eines neuen Hintergrund und Layouts.

## 08.09.2021 
Antonia ist wieder krank. Heute hatte die ganze Klasse technische Probleme, die wir jedoch nach etwas Zeit lösen konnten. Leider hatte unser Computer weiterhin Probleme, weshalb wir uns einen neuen Computer suchen mussten der funktioniert. Als wir schließlich einen Computer gefunden haben, haben wir die restlichen Bilder auf alle Seiten eingefügt und uns vorgenommen, nächste Stunde den Code, den wir auf einer Seite getestet haben, auf jede Seite zu übertragen und uns mit alten Problemen (z.B. wie kann man eine eigene Spalte erstellen?) befassen.

## 14.09.2021
Augefallen.

## 15.09.2021
Ausgefallen.

## 21.09.2021
Farhat und Antonia sind heute krank. Wir haben endlich herausgefunden, wie man eine Liste erstellt zu der man neue Items hinzufügen kann. Diesen Code haben wir heute angefangen zu schreiben und mussten dementsprechend viele bereits bestehenden Funktionen und Codes löschen. Während wir vorher einzelne Textboxen hatten, in die man jeweils einzeln ein Objekt eintragen kann, kann man jetzt durch einen "add" Button aus beliebig vielen Dingen eine Liste erstellen. Auch die "Check" Buttons, die neben jeder Textbox war, um diese durch Drücken des Buttons einzufärben und als erledigt zu markieren, mussten durch den neuen Code weichen. 
Außerdem können wir jetzt das Datum und die Uhrzeit auf der ersten Seite einstellen.

## 22.09.2021
Farhat ist zurück. Wir haben die große Umstellung vom Tag davor vollendet und sowohl das neue Layout angelegt, als auch den neuen Code zu Ende entwickelt.

![alte Liste](https://user-images.githubusercontent.com/88386173/137929733-53e957e5-9ddf-40f2-ad66-0833e9783685.png)

-----------------------------------------------------------------------------------------

![Drogeriescreenblocks nah](https://user-images.githubusercontent.com/88386173/137927122-5b138bad-9c25-473d-b039-e663fcf76ec0.png)

Dies ist der neue Code am Beispiel des Drogerie-Screens. Statt vielen einzelnen Textboxen, die man durch Buttons neu generieren und einfärben kann, gibt es nun ein Feld, in welches man tippt und durch einen einzigen Button wird dann automatisch eine Liste generiert. Oben sieht man im Vergleich den alten Code, bei welchen man für jede Textbox einzeln eine Funktion programmieren musste, sodass man dort reinschreiben kann.

![neues Layout](https://user-images.githubusercontent.com/88386173/137927903-bf36b968-48d7-4492-a8ce-bbd57118b2ee.png)

![drogeriescreenn](https://user-images.githubusercontent.com/88386321/138899470-1da780fb-7d9b-428a-9e4a-0416aa9815e7.png)

Dies ist nun das neue Layout, welches dank weniger Knöpfe und Buttons und effizienteren Codes übersichtlicher ist und besser funktioniert.

![Homescreen1](https://user-images.githubusercontent.com/88386173/137930091-cafdc5f2-99f3-4fc0-bf77-017ec750e2c2.png)

![Uhrzeit](https://user-images.githubusercontent.com/88386173/137928390-a9d2fc89-e61b-449a-aa75-4b0056ca1f04.png)

Dies ist der erste Code für die Uhrzeit und das Datum. Darüber sieht man, wie diese auf dem Homescreen positioniert sind.

## 28.09.2021
Die ganze Gruppe war durch Krankheit verhindert.

## 29.09.2021
Die Klasse hat ihr Deutsch-Vorabi geschrieben.

## 05.10.2021
Herbstferien

## 06.10.2021
Herbstferien

## 12.10.2021
Herbstferien

## 13.10.2021
Herbstferien

## 19.10.2021
Heute hat sich unsere Gruppe aufgeteilt. Während Antonia den GitHub-Blog überarbeitet, auf Vollständigkeit prüft und mit Bildern füllt, arbeiten Vanessa und Farhat an einer Möglichkeit, die Objekte in einer Liste auch zu speichern. Denn momentan gehen diese verloren, wenn man auf einen anderen Screen wechselt. In Teamarbeit haben wir uns auch dazu entschieden, für die Präsentation ein Werbevideo zu drehen, über dessen Inhalt wir kurz gebrainstormt haben.
Inhalt:
Bild 1: Personen, in einem Supermarkt/Drogeriemarkt/..., welche eine hohe Anzahl an Einkaufszetteln durchwühlen und fallen lassen (schneller Cut zwischen diesen Personen)
Bild 2: Aufnahme einer einfarbigen Oberfläche von oben, ein Handy wird vom Rand in die Mitte des Tischs gestoßen, die Kamera zoomt auf den Bildschirm, wo unsere App offen ist
Bild 3: Bildschirmaufnahme, die App wird benutzt (--> Slogan: einfacher als tausend Zettel!)
Bild 4: Slogan? Logo?
Diese Idee haben wir später verworfen und uns dazu entschieden, uns mehr auf die App zu konzentrieren.

![speichern](https://user-images.githubusercontent.com/88386321/138896300-73f29c1d-579c-40ad-8a70-bb862f355871.PNG)

Dieser Code wurde upgedatet. Die lila Kästen sind neu und ermöglichen das Speichern der Items auf der Liste.

## 20.10.2021
Wir konnten erfolgreich neue Items in unseren Listen speichern, haben jedoch in dieser Stunde herausgefunden, dass die Items nicht nur in einer Liste, sondern in allen Listen gleichzeitig gespeichert werden. Wir werden probieren, das Problem in der kommenden Stunde zu beheben. Außerdem hat Antonia heute ein Android Handy von Zuhause mitgenommen, sodass wir unsere App heute auch auf einem Handy ausprobieren konnten. Dies hat sehr gut geklappt. Zur Sicherheit haben wir zudem verschiedene Screenshots von den Codes gemacht, damit wir diese nicht verlieren. 

![speichern](https://user-images.githubusercontent.com/88386321/138898700-3f13e8e0-0205-49ae-bfbd-2a4e19842803.PNG)

## 26.10.2021
In dieser Doppelstunde haben wir das Speicher-Problem der Listen behoben. Indem wir alle Listen gleich benannt haben, wurden alle Items auf jeder Liste gespeichert. Nachdem wir die Listen unbenannt haben, funktionierte es wie geplant. Auch haben wir einige Soundeffects herausgesucht und in die App eingesetzt. Wir haben uns aber dazu entschieden, dass  nur eine kleine Klingel läuten soll, wenn man einen der Läden auswählt, damit es sich anfühlt, als würde man wirklich einen Laden betreten. Alle anderen Soundeffects empfanden wir dann doch als zu viel, da diese auch schnell nerven können. Ganz nach dem Motto "weniger ist manchmal mehr", beließen wir es bei der Klingel. 

![soundcode](https://user-images.githubusercontent.com/88386321/138890689-a545e681-08b4-471d-87ad-702cc3c0d949.PNG)

Danach haben wir das Problem, dass man das Datum und die Uhrzeit zwar einstellen kann, das Programm sich diese aber nicht merkt, gelöst. Als Erstes sieht man den alten Code und darunter zum Vergleich den neuen. Unsere eigentliche Idee war es,  "tinyDB" als Database zum Speichern zu nutzen. Dies hat nicht funktioniert, da man dann folgend die Daten und Uhrzeiten selbst eintragen muss, weshalb wir eine Formatierung bestimmen mussten, die das Handy dann automatisch zu einer Uhrzeit/Datum generiert:

![Uhrzeit](https://user-images.githubusercontent.com/88386321/138898937-4e89d015-97ad-4c1f-9033-bfb0a8222dd0.png)

--------------------------------------------------------------------

![newclock](https://user-images.githubusercontent.com/88386173/139058003-1c0bd9ff-7f12-4e60-bb53-7af4dc9b2f82.PNG)

Und hier das finale Layout des Start-Screens:

![Homescreenshot](https://user-images.githubusercontent.com/88386321/138899019-abf09a45-2222-48ca-a3a3-c736d73c6b46.png)

## 27.10.2021
Heute haben wir Ordnung in unsere App gebraucht. Zuerst haben wir unnötige Features, die noch von alten Codes übrig waren, entfernt. Auch haben wir mehrere Zwischenversionen von unserem Projekt als Notsicherung, falls ein Coding-Versuch schiefgeht, gehabt. Diese haben wir nun alle miteinander verglichen, damit unsere Originalversion auf dem neusten Stand ist und dann gelöscht, da wir sie nicht mehr brauchen.

## 02.11.2021
Heute war Farhat krank. Wir haben die App verschönert und einige Details, die wir ändern wollten, geändert. 
Dies sind die neuen Layouts der Screens:

![start](https://user-images.githubusercontent.com/88386173/143043488-b59ba550-436d-4daa-82f6-08525570f744.png)

Der neue Home-Screen.

![auswahl](https://user-images.githubusercontent.com/88386173/143043525-84d5ee52-1338-4606-88c2-47072313dddb.png)

Der neue Auswahl-Screen.

![clothe](https://user-images.githubusercontent.com/88386173/143043579-636aac83-d800-4334-9115-72ee8a7eaf87.png)
![drogerie](https://user-images.githubusercontent.com/88386173/143043604-89ab2472-4a8c-4ac3-a0b3-b9f8541998ca.png)
![supermarkt](https://user-images.githubusercontent.com/88386173/143043616-829a33bc-0e12-4a6b-b6a6-3257cfec4ac0.png)

Die neuen Einkaufslisten.

## 03.11.2021 
Antonia ist krank. Sie wird von Zuhause arbeiten und fängt mit unserer PowerPoint-Präsentation an. In der Schule hat Vanessa Farhat die neuen Änderungen gezeigt. Anschließend wurden die restlichen Screens eingestellt.

## 09.11.2021
Die Klasse hat ihr Mathematik-Vorabi geschrieben. 

## 10.11.20212 
Antonia und Farhat sind krank. Die Stunde hat etwas später als üblich angefangen, da der Computerraum abgeschlossen war und Herr Buhl noch in einer Konferenz war. Da die App so weit funktioniert, hat sich Vanessa Gedanken zum Projekt gemacht und Ideen gesammelt, inwieweit wir unsere App z.B. noch verbessern können (neue Features, besseres Layout...). Ihre Idee ist es, einen weiteren Screen namens "Map" zu erstellen. Für diesen Screen würden wir einen Navigations-Screen codieren, damit Personen, die die App benutzen, gleich in der App den Weg zu ihrem Store finden können. 

## 16.11.2021
Wir haben zusammen über weitere Ideen nachgedacht. Wir werden einen weiteren Screen erstellen, auf welchem wir Webseiten verlinken, beziehungsweise, die Webseiten sind in die App eingebettet. Diese haben alle etwas mit Einkaufen zu tun, wie zum Beispiel ein Rewe Bringdienst, Amazon, oder Chefkoch. Folgend hat Antonia hat die Präsentation weiterbearbeitet. Farhat und Vanessa haben an der neuen Idee gearbeitet.

## 17.11.2021
Wir haben an den Weblinks weitergearbeitet. Der Code ist fertig geworden und wird am nächsten Dienstag getestet. 

## 23.11.2021
Während Antonia weiter an dem GitHub und an der Präsentation gearbeitet hat, haben Farhat und Vanessa Töne für die Buttons gesucht, die beim Drücken abspielen. Die Webseiten in unserer App funktionieren besser als gedacht. Auch hat Herr Buhl sich unsere App angeschaut. Antonia hat herausgefunden, wie sie die Farben des Textes bei GitHub ändert und kopierbare Textboxen erstellt. Gegen Ende der Stunde haben wir bei dem Amazon-Link einen Fehler erkannt und diesen behoben. Zum Schluss haben wir noch Screenshots von allen neuen Codes und Screens gemacht, um diese nächste Stunde in den GitHub-Blog und die PPP einzufügen. 

## 24.11.2021
An diesem Mittwoch haben wir uns darüber informiert, wie wir unsere App nach der Fertigstellung teilen können. Wir haben einen schnellen, effizienten Weg gefunden, die App als APK-Datei direkt auf das Handy zu laden und zu speichern. Diesen Vorgang haben wir heute erstmal mit einem Probe-Projekt geübt, damit nichts verloren geht, wenn etwas schiefgeht. 
So sieht der neue Code für die neuen Webseiten aus und danach sieht man noch das Layout im Editor:

![websitesblock](https://user-images.githubusercontent.com/88386173/144067582-427f3697-cd65-41f6-8b33-197ea2c79f3c.PNG)

![websites](https://user-images.githubusercontent.com/88386173/144067597-f7c6b2ba-0f48-48a3-97b2-80724d86ab9b.PNG)

Hier sind die neuen Screens, in die wir Chefkoch, Rewe und Amazon eingebettet haben:

![Screen_Amazon](https://user-images.githubusercontent.com/88386173/144064283-170b06e1-5f97-47d6-ab25-bfa4c6641543.png)

![Screen_Rewe](https://user-images.githubusercontent.com/88386173/144064297-be91047f-9470-4b2b-92ab-89932c5aa6f3.png)

![Screen_Chefkoch](https://user-images.githubusercontent.com/88386173/144064306-cf7521b9-7781-476d-8673-d0774ddf9ac7.png)

## 30.11.2021
Wir haben uns vorgenommen, heute so viel wie möglich fertigzustellen, da in einer Woche Abgabe ist. Dafür haben wir uns aufgeteilt. Während Antonia ein Logo designt und GitHub auf Vollständigkeit und Rechtschreibung prüft, suchen Farhat und Vanessa Möglichkeiten, die App Inventor Website, mitsamt Codes zu teilen. Anschließend haben wir die App auf 30 mb verkleinert, indem wir unnötige uploads, wie alte Töne oder Bilder gelöscht haben. Die App wurde dann von uns auf unser Android-Handy, als auch das Schultablet geladen. 

## 01.12.2021
Heute haben wir unsere Arbeit beendet. Wir haben kontrolliert, ob die App auf beiden Geräten läuft. Dann haben wir sie bei AppInventor selbst in der Gallerie geteilt, damit man online auf die Codes zugreifen kann. Final haben wir alle Links in GitHub hinzugefügt.

### <a name="3"></a>Fazit

Wir sind mit unserer App zufrieden, da diese besser funktioniert, als wir es uns anfangs gedacht hatten. Natütlich ist es kein Meisterwerk der Programmierkunst, aber wenn man unsere nicht vorhandenen Vorkenntnisse bedenkt, sind wir stolz auf uns. Besonders freuen wir uns über unsere Endresultate, da wir in jedem einzelnen Code sehen, wie wir uns verbessert haben und effizienter geworden sind. Das Projekt hat uns sehr gefallen und wir sind über uns hinaus gewachsen und haben viel gelernt. Nächstes Mal würden wir vielleicht ein anderes Programm verwenden, da AppInventor doch manchmal stockend lief und uns in unseren Möglichkeiten begrenzt hat.

### <a name="4"></a>Finale Links

Link um die App auf ein Android-Gerät zu downloaden:

```diff 
https://we.tl/t-Y5zFp8DbfR
```
--> Die App wurde bereits auf das Schultablet geladen (läuft dort aber langsam). In den Informatikstunden können Sie sich die App auch auf unserem Handy anschauen.

Link AppInventor, um die Codes anzuschauen:

```diff 
https://gallery.appinventor.mit.edu/?galleryid=796cbe04-672f-491a-bed6-6ce542385db7
```

Hinweis: Klicken Sie auf "Load App Into MIT App Inventor". Sie brauchen allerdings ein Google-Konto, um sich bei App-Inventor anzumelden. Sonst könnten wir Ihnen auch in einer Informatikstunde unsere Konten zur Verfügung stellen.

### <a name="5"></a>Projektseite als PPP

PowerPoint-Präsentation: [Informatik_Kladde.pptx](https://github.com/akabg/Informatik-12.1/files/7655958/Informatik_Kladde.pptx)

PDF PowerPoint-Präsentation:[Informatik_Kladde.pdf](https://github.com/akabg/Informatik-12.1/files/7655956/Informatik_Kladde.pdf)
