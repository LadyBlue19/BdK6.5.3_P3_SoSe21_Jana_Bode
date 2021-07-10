# Aufgabe 1 in BDK6.5.3 (wB/öB) P3 Data Librarianship und Programmierung

## - Text-Editor meiner Wahl -
ich habe mich für Notepad++ entschieden.
## - Eine Python-Bibliothek -
### NLTK
Was macht NLTK? -> verarbeitet und analysiert Daten
 
Wie kann man diese nutzen? -> Verarbeitung der natürlichen Sprache (Menschensprache)
## - Eine Fehlermeldung und Ihre Lösung -
Fehler: ich hatte am Anfang die URL falsch aufgeschrieben und falsch aufgeteilt, wehsalb ich nur eine zeile als Antwort zurück bekam: 
base_url = "https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pubmed&retmode=json"
doi = "27708327"
full_url = base_url + doi

Lösung: nachdem meine Gruppenmitgleider mich darauf hingewiesen haben, habe ich es dann verbessert, so dass ich letztendlich an meiner Aufgabe weiter arbeiten konnte:
base_url = "https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pubmed&retmode=json&id="
doi = "27708327"
full_url = base_url + doi
## -  Was ist JupyterLab? -
JupyterLab ist eine Benutzeroberfläche im Web-Format und gehört zum "Project Jupyter". Für Datenwissenschaftler bietet es eine interaktive Entwickulngsumgebung, da es mit Jupyter Notebooks, Codes und Daten arbeiten kann. Man kann sagen, dass JupyterLab eine bessere und ausgerbaietet Alternative zu JupyterNotebook ist.
## - Was ist der große Unterschied zwischen den Webframeworks flask und Django? -
Django scheint komplexer als Flax zu sein und hat ein eigenes ORM. Flax bietet dagegen mehr Flexibilität und hat den Fokus auf kleinere Programme mit geringen Anforderungen gelegt.
