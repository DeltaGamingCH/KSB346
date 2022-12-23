# AWS ImageResize Dokumentation

## Inhaltsverzeichnis

Vorwort<br>
Installation<br>
Benutzung<br>
Schlusswort<br>
Erstellen

## Vorwort

Im Informatik Modul 346 haben wir, Claude, Qouc Hung, Nikita, den Auftrag eine Cloud zu entwickeln, welche ein Bild als Input nimmt und dieses verkleinert. 

## Installation

Wichtig ist, dass man die Amazon CLI installiert hat. Das ist eine Befehlszeilenschnittstelle welche mit dem AWS von Amazon interagieren kann. Ohne diese Brücke ist das ganze nicht möglich.

Um den Amazon Client zu installieren, 

Um dies zu machen, muss man auf Amazon gehen und eine Datei herunterladen. Um die Installation abzuschliessen und zu bestätigen muss man das CMD im normalen Windows geöffnet werden und den command "aws --version" eingeben. Nun ist die Instalation erforlgrech abgeschlossen. Im Anschluss wird diese noch eine wichtige Rolle spielen.

## Erstellen 

In den letzten Lektionen vor der Abgabe begannen wir mit unserem Projekt, da wir die Woche zuvor alle krank waren. Mit dem Code, welchen wir während dem Unterricht erarbeitet haben kamen wir nicht sehr weit, konnten jedoch die CleanUp Funktion und teils die Setup Funktion erstellen. 
Fragen an Sie wollten wir keine stellen, da wir von anderen gehört haben, dass sie das OneNote verlinken und einen kleinen Input dazu geben. Dies war uns aber nicht genug, wir brauchten eine Struktur im Code. Das Wissen dafür hat uns gefehlt. 

Wir wandten uns an die Klasse und arbeiteten gemeinsam am Projekt weiter. Nach einem Austausch kamen wir zum Entschluss unseren Code zu löschen, damit wir auf der sicheren Seite sind, dass der Code auch funktioniert.  
Wir teilten verschiedene Funktionen voneinander. 
Setup, welches die Buckets erstellt und die Lambdafunktion aufruft. 
Cleanup, die Dateien und Buckets werden wieder gelöscht. 

Wir erstellten mit .js eine Funktion, welche Mithilfe des "export-handlers" die Datei anschliessend zurück schickt. Die Lambdafunktion an für sich ist dazu da, das Bild zu verkleinern, dazu werden aber auch die Variablen in config.js benötigt. 

Wir bauten während des Script-erstellung überall "echo" ein, damit wir einen Output zu unserem Projekt bekommen. Funktioniert alles wie es soll, wird "Status Code 200" ausgegeben. 

## Benutzung
Zwei Buckets werden bei der Ausführung des Script erstelltn, sobald ein Bild dazu existiert.
Das Bild wird anschliessend in der Pixelzahl verkleinert, wird ausgegeben und die Buckets werden wieder gelöscht.

## Reflexion
Nicht nur war es sehr anstrengend am Thema zu arbeiten, sondern es war auch sehr Zeitaufwendig. 
Unglücklicherweise ist Claude nicht zurzeit des Projekts erreichbar gewesen, ich die letzten zwei Tage vor Abgabe krank gewesen. Mit diesen Umständen beschlossen wir auf die Klasse zu zugehen und nachzuhaken, wie weit unsere Mitschüler waren. Keiner der Gruppen hatte am Abgabetag ein funktionierendes Projekt, andere wussten nicht weiter. 
Wir kamen als Klasse zusammen und begannen zusammen am Projekt zu arbeiten. Für die Dokumentation beschlossen wir, jeder diese einzeln zu machen. 
Das Projekt war für uns zwei über unserem Schwierigkeitsgrad. Ich geh davon aus, dass es an der fehlenden Übung von Shell und der generellen Cloud-Programmierung gelegen hat. 
