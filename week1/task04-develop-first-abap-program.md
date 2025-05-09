✅ Developing Your First ABAP Program – 'Hello World' Application
Ziel: Entwicklung einer "Hello World" App in ABAP
Objective: Create a 'Hello World' application in ABAP

Overview / Übersicht
In this lesson:

You'll write a simple "Hello World" application to familiarize yourself with the ABAP development environment.

Key Interface:

Use IF_OO_ADT_CLASSRUN to run the program as a console app in Eclipse.

Distinguishing Fiori and ADT:

Fiori Elements: The main UI technology for modern ABAP applications, used for building rich, front-end interfaces.

ADT (ABAP Development Tools): Provides a console output for quick test applications and streamlined development.

Task 1: Create a Hello World Application / Aufgabe 1: Erstellen einer "Hello World" Anwendung
German / Deutsch | English
Erstelle eine neue ABAP-Klasse in deinem Paket.
Create a new ABAP class in your package.

Klasse benennen:

German: Gib der Klasse den Namen ZCL_##_HELLO_WORLD (wobei ## für deine Gruppennummer steht) und trage eine Beschreibung ein.

English: Name the class ZCL_##_HELLO_WORLD (with ## as your group number) and provide a description.

Implementierung der Schnittstelle:

German: Wähle im Dialog neben dem Feld "Interfaces" die Schaltfläche Add…, gib IF_OO_ADT_CLASSRUN als Filtertext ein, wähle den entsprechenden Eintrag aus und bestätige.

English: Click Add... (next to the Interfaces group box), enter the filter text IF_OO_ADT_CLASSRUN, select it from the list, and confirm.

Transportauftrag:

German: Wenn du zur Zuweisung eines Transportauftrags aufgefordert wirst, wähle den Transportauftrag, den du im vorherigen Task erstellt hast.

English: When prompted for a transport request, select the one you created previously.

Erstelle die Klasse:

German: Wähle File → New → ABAP Class in Eclipse, gib dein Paket (ZS4D400_##) und den Klassennamen ein, und klicke auf Finish.

English: From Eclipse, choose File → New → ABAP Class, enter your package (ZS4D400_##) and the class name, then click Finish.

Code in der Hauptmethode einfügen:

German: Im if_oo_adt_classrun~main( )-Methode füge zwischen METHOD if_oo_adt_classrun~main und ENDMETHOD folgenden Code ein:

out->write( 'Hello World' ).
English: In the if_oo_adt_classrun~main( ) method, insert the following code between METHOD if_oo_adt_classrun~main and ENDMETHOD:

out->write( 'Hello World' ).
Klasse aktivieren und testen:

German: Aktiviere die Klasse mit Ctrl + F3 und führe sie mit F9 aus. Überprüfe die Ausgabe im Console-View. Falls die Konsole nicht automatisch sichtbar ist, wähle Window → Show View → Other und öffne die Konsole.

English: Activate the class using Ctrl + F3 and run it with F9. Check the output in the Console view. If the Console is not visible, choose Window → Show View → Other and open the Console.

Unterscheidung: ADT vs. Fiori

German: Diese Übung verwendet ADT, um schnell eine Konsolenanwendung zu erstellen. Für moderne ABAP-UI-Entwicklung solltest du jedoch Fiori Elements kennenlernen, da diese für umfassende und interaktive Oberflächen genutzt werden.

English: This exercise uses ADT for creating a quick console application. However, for modern ABAP UI development, you should become familiar with Fiori Elements, which are used to build comprehensive and interactive user interfaces.

:

🇩🇪 Herausforderungen und Lösungen (kurz):
❌ Herausforderung: Nach dem Schreiben der Klasse erschien keine Ausgabe in der Konsole.

🎯 Ursache: Die Klasse war noch nicht aktiviert, daher konnte sie nicht ausgeführt werden.

✅ Lösung: Die Klasse wurde aktiviert und dann über ADT als „ABAP-Anwendung (Konsole)“ ausgeführt.

🧠 Erkenntnis: ABAP-Code muss immer aktiviert werden, bevor er im System lauffähig ist.

🇬🇧 Challenges and Solutions (short):
❌ Challenge: No console output appeared after writing the class.

🎯 Cause: The class was not yet activated, so it couldn’t be executed.

✅ Solution: The class was activated, and then run as an "ABAP Application (Console)" via ADT.

🧠 Insight: ABAP code must be activated before it becomes executable in the system.