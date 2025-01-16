Credit Card Fraud Detection

Problemstellung

Kreditkartenbetrug umfasst die Verwendung einer fremden Kreditkarte für finanzielle Transaktionen ohne das Wissen des Karteninhabers. Dies führt zu erheblichen wirtschaftlichen Verlusten weltweit, geschätzt auf mehr als 24 Milliarden Dollar pro Jahr. Der Anstieg des E-Commerce und der OTT-Plattformen während der Coronavirus-Pandemie hat den Einsatz von Kreditkarten exponentiell erhöht. Dies hat auch zu einer Zunahme von Betrugsfällen geführt. Unsere Aufgabe ist es, ein automatisiertes Modell zu entwickeln, das betrügerische von legitimen Transaktionen unterscheiden kann.

Ziel

Das Ziel dieses Projekts ist es, zu klassifizieren, ob eine Kreditkartentransaktion betrügerisch oder legitim ist. Es handelt sich um ein binäres Klassifikationsproblem mit stark unausgeglichenen Daten.

Dataset

Das Dataset enthält Transaktionen, die im September 2013 von Kreditkarteninhabern in Europa durchgeführt wurden. Es umfasst 284.807 Transaktionen über zwei Tage, von denen 492 als Betrug klassifiziert sind. Die positive Klasse (Betrug) macht nur 0,172% aller Transaktionen aus.

Attribute
	•	V1 - V28: Numerische Merkmale, die das Ergebnis einer PCA-Transformation sind.
	•	Time: Sekunden seit der ersten Transaktion im Datensatz.
	•	Amount: Transaktionsbetrag.
	•	Class: Betrug (1) oder kein Betrug (0).

Inhalte des Notebooks
	•	Dataset-Informationen
	•	Datenvisualisierung
	•	Auswahl der Merkmale
	•	Datenausgleich
	•	Modellierung
	•	Schlussfolgerung
