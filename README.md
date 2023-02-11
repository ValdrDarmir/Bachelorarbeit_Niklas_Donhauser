# Implementierung und Evaluation verschiedener Machine Learning-Ansätze für die Sentiment-Analyse im Deutschen
Name: Niklas Donhauser
<hr>

## Abstract <br>

In English-speaking countries, machine learning approaches are often used for sen-
timent analysis. In other languages such as German, there is not yet a comprehensi-
ve analysis of different machine learning approaches on same-language corpora. This
paper attempts to fill this gap by evaluating seven different approaches on 20 with
sentiment annotated corpora. With the help of the cross-evaluation, recommenda-
tions can be made for the different domains in the future work.
For this purpose, pre-processing steps were performed on all corpora for classi-
cal approaches and neural networks. Furthermore, sub-studies investigated the in-
fluence of such preprocessing steps on transformer-based approaches. In addition,
the Base and Large variants of two transformer models were compared.
The cross-evaluation examined all approaches on each corpus in dichotomous
and trichotomous polarity, using metrics such as accuracy and the F1-measure to
rank the results.
On average, the GBERT model showed the best results, achieving an F1-measure
of 78.23 % across all corpora. A maximum F1-measure of 92.77 % was achieved in
the domain of product evaluations.
Based on the results in this work, no preprocessing is recommended in most cases
for transformer-based approaches. The use of the Large variant should also be used
in most cases.

## Zusammenfassung <br>

Im englischsprachigen Raum werden für die Sentiment Analyse häufig maschinelle
Lernverfahren eingesetzt. In anderen Sprachen wie dem Deutschen gibt es noch kei-
ne umfassende Analyse von verschiedenen Machine Learning-Ansätzen auf gleich-
sprachigen Korpora. Diese Arbeit versucht diese Lücke zu schließen, indem sieben
verschiedene Ansätze auf 20 mit Sentiment annotierten Korpora evaluiert werden.
Mithilfe der Kreuzevaluation können Empfehlungen für verschiedene Domänen in
zukünftigen Arbeiten ausgesprochen werden.
Dazu wurden bei klassischen Ansätzen und neuronalen Netzen vorverarbeiten-
de Schritt auf allen Korpora durchgeführt. Weiterhin untersuchten Unterstudien
den Einfluss solcher vorverarbeitender Schritte auf Transformer-basierten Ansät-
zen. Außerdem wurden die Base und Large Varianten von zwei Transformer-Modellen
miteinander verglichen.
Die Kreuzevaluation untersuchte alle Ansätze auf jedem Korpus in dichotomer
und trichotomer Form, wobei Metriken wie Accuracy und der F1-Wert zur Einord-
nung der Ergebnisse verwendet wurden.
Im Durchschnitt zeigte das Modell GBERT die besten Ergebnisse und erreichte
über alle Korpora verteilt einen F1-Wert von 78,23 %. Dabei wurde ein maximaler
F1-Wert von 92,77 % in der Domäne der Produktbewertungen erreicht.
Aufgrund der Resultate in dieser Arbeit wird in den meisten Fällen bei transformer-
basierten Ansätzen kein Preprocessing empfohlen. Die Verwendung der Large-Variante
sollte ebenfalls in den meisten Fällen verwendet werden.

## Aufbau

**1_Ausarbeitung**

- Schriftliche Ausarbeitung der Arbeit als PDF
- Schriftliche Ausarbeitung von Overleaf

**2_Code**

- Alle Jupyter Notebooks dieser Arbeit

**3_Quellen**

- Liste der Quellen die in dieser Arbeit verwendet wurden 

**4_Tabellen**

- Alle Excel-Tabellen
- Zeitliche Tabellen als PDF

**5_Vorträge**

- Antrittsvotrag als PDF
