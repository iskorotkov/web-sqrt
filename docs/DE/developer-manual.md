**Beschreibung der globalen Variablen**:

*config* - Wörterbuch zum Speichern der Einstellungen der Anwendung.

*dictRu* - Wörterbuch, das die Übersetzung der Benutzeroberfläche ins Russische speichert.

*dictEn* - Wörterbuch, das die Übersetzung der Benutzeroberfläche ins Englische speichert.

*dictDe* - Wörterbuch, das die Übersetzung der Benutzeroberfläche ins Deutsche speichert.

*dictEs* - Wörterbuch, das die Übersetzung der Benutzeroberfläche ins Spanische speichert.

*dictFr* - Wörterbuch, das die Übersetzung der Benutzeroberfläche ins Französische speichert.

*allDicts* - Wörterbuch, das Wörterbücher für den gesamten Satz von Sprachen speichert.

*valueInput* - UI-Element, in dem der vom Benutzer eingegebene Wert gespeichert wird.

*resultInput* - UI-Element, das den Ergebniswert der Quadratwurzelberechnung speichert.

*precisionInput* - UI-Element, das den Wert der signifikanten Ziffern speichert.

*precisionSlider* - UI-Element, das mit dem Schieberegler zur Änderung des Wertes der signifikanten Stellen verbunden ist.

*digitsAfterPointInput* - das UI-Element, das den Wert der Ziffern nach dem Dezimalpunkt speichert.

*digitsAfterPointSlider* - das mit dem Schieberegler verknüpfte Oberflächenelement, um den Wert der Nachkommastellen zu ändern.

*languageSelect* - UI-Element, das die aktuell ausgewählte Sprache speichert.

**Funktionsbeschreibung**:

*ClampDigits*.

- Beschreibung: Trimmt die Anzahl der Stellen nach dem Dezimalpunkt für die Ausgabe auf den angegebenen
- Eingangsparameter:
  - *Wert* - Zahl, für die die Anzahl der Nachkommastellen eingestellt ist

*Klammer*

- Beschreibung: begrenzt die Anzahl der Ziffern im angegebenen Bereich
- Eingangsparameter:
  - *Präzision* - Zahl
  - *min* - Mindestwert
  - *max* - Maximalwert

*setPrecision*

- Beschreibung: setzt den Genauigkeitswert für die resultierende Zahl 
- Eingangsparameter:
  - *Präzision* - Genauigkeitswert

*setDigitsAfterPoint*

- Beschreibung: bestimmt den Wert der Anzahl der Nachkommastellen für die Ergebniszahl 
- Eingangsparameter:
  - *Digits* - Wert der Anzahl der Nachkommastellen

*setPrecisionSupported*

- Beschreibung: Legt die Unterstützung der Genauigkeit fest, abhängig vom Wert des Merkerwertes 
- Eingangsparameter:
  - *Wert* - der logische Wert des Flags

*updateResult*

- Beschreibung: Berechnet den Quadratwurzelwert und aktualisiert den Wert der Ausgangsvariablen

*updateLanguage*

- Beschreibung: aktualisiert die Textbeschreibung der UI-Elemente, wenn die Sprache geändert wird
