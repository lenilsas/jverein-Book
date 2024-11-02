# Rechnungen drucken/mailen

## Allgemeines

Für alle Sollbuchungen können Rechnungen erstellt werden. Dabei hat man die Möglichkeit eine Rechnung selektiv oder automatisch zu erstellen.

Möchten Sie Rechnungen direkt aus JVerein druckfertig generieren, so müssen Sie mindestens ein Rechnungsformular angelegt haben. Die Erstellung von Rechnungsformularen ist unter Administration\|Formulare beschrieben.

Die Rechnungen können für den Druck in ein PDF-Dokument ausgegeben werden oder per Mail an die Mitglieder versandt werden.

## Rechnungen selektiv erstellen

Möchten Sie eine Rechnung selektiv erstellen, so öffnen Sie den Dialog Sollbuchungen. Wählen Sie den Filter so, dass die gewünschten Daten angezeigt werden. Selektieren Sie einen oder mehrere Einträge und drücken die rechte Maustaste. Es öffnet sich ein Kontext-Menü. Wählen Sie hier den Menüpunkt "Rechnung erstellen". Es öffnet sich hier der Dialog Rechnung der Sie bei der Erstellung der Rechnung unterstützt.

Hier lässt sich bei der Ausgabe zwischen Drucken oder Versenden per Mail wählen.

Im Info Feld wird angezeigt wieviele Sollbuchungen selektiert wurden und ob  zugehörige Mitglieder keine Mailadresse haben. Haben sie keine Mail Adresse werden sie beim Versand per Mail ignoriert.

![](../../assets/mitgliedrechnung2.png)

Im Parameter Feld "Formular" ist ein Formular auszuwählen. Dieses muss gegebenenfalls erstellt werden. Siehe [Formulare](../administration/mitglieder/formulare.md).

Im Parameter Feld "Ausgabe" lässt sich wählen ob die Rechnungen als PDF gedruckt oder per Mail verschickt werden sollen.

Im Falle des Mail Versand sind die Felder Betreff und Text auszufüllen.

Über die Buttons lässt sich eine gespeicherte Mailvorlage auswählen bzw. die Rechnung exportieren.

Das drücken des Startknopf löst im Fall der Mail Ausgabe bei korrekt eingestellten Mail-Server-Daten den Versand der Mails aus. Es ist daher ratsam, diese Funktion im Vorfeld zu testen, ohne mit echten Mitgliederdaten/Mails zu hantieren.

## Rechnungen automatisch erstellen

Um automatisch Rechnungen zu erstellen wählen Sie im Navigations Baum dem Menü Eintrag "Rechnungen" aus. Es öffnet sich ebenfalls der Dialog Rechnungen.

Im Gegensatz zum selektiven Erstellen wird hier der gleiche Filter Bereich angezeigt wie im Sollbuchungen Dialog. Es werden dann Rechnungen für alle Sollbuchungen die die Filter Kriterien erfüllen gedruckt bzw. per Mail versendet.

![](../../assets/mitgliedrechnung1.png)

Der Filter Bereich bietet folgende Optionen:
* Name: Der Name eine Mitglieds.
* Differenz: Bei "Fehlbetrag" werden nur Kontoauszüge für Mitglieder erstellt wenn ein Fehlbetrag vorliegt und bei "Überzahlung" nur wenn überzahlt wurde. Bei "Egal" wird nicht auf den Betrag geprüft.
* Ohne Abbucher: Schliest Mitglieder die per Lastschrift bezahlen aus.
* Datum von/bis: Es werden nur Mitgliedskonten Einträge im gewählten Zeitraum berücksichtigt.
* Mail: Hier lässt sich auswählen ob nur Mitglieder mit Mailadresse, ohne Mailadresse oder unabhängig von einer Mailadresse ausgewählt werden.

Tip:

Falls Sie Rechnungen per Mail versenden wollen, wählen Sie erst bei Mail die Option "Nur mit Mailadresse" und als Ausgabe MAIL. Damit versenden sie die Rechnung an alle Mitglieder die eine Mail Adresse haben.

Falls nicht alle Mitglieder eine Mail Adresse haben, wählen Sie anschliesend bei Mail die Option "Nur ohne Mailadresse" und die Ausgabe DRUCK. Diese können Sie dann per Post verschicken.

## Rechnungen drucken

Es öffnet sich ein Dialog der den Speicherort und den Dateinamen der PDF Datei abfragt, in die alle Rechnungen erstellt werden. Mit Bestätigen dieser Eingaben werden die Rechnungen generiert und die fertige PDF geöffnet. Diese können Sie nun ausdrucken.

## Rechnungen per Mail versenden

Rechnungen können per Mail versandt werden. Dazu muss die Mailkonfiguration abgeschlossen sein. Bei der Ausgabe wird zu Kontrollzwecken eine ZIP-Datei mit allen erstellten und versandten Rechnungen erstellt.

## Rechnungsdaten exportieren

Sollen die Rechnungsdaten exportiert werden, so drücken Sie im Dialog Rechnung den Schalter Export. Es öffnet sich ein Dialog der den Speicherort und den Dateinamen der CSV abfragt. Bestätigen Sie diesen Dialog, werden die Rechnungsdaten in diese Dateien exportiert und können danach z.B. für einen Serienbrief verwendet werden.

Für die einzelnen Zahlungswege können Texte unter Administration\|Einstellungen\|Rechnungen hinterlegt werden.