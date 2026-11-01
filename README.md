# LLM-basierte Fragebogenentwicklung zur KI-Readiness

Begleitmaterial zur Hausarbeit „Potenziale und Herausforderungen LLM-basierter Fragebogenentwicklung: Eine Evaluation methodischer Leitlinien am Beispiel der KI-Readiness“.

## Forschungsfrage

Wie müssen methodische Leitlinien gestaltet sein, damit ein LLM auf Basis vorgegebener Textkorpora theoriegeleitet valide Fragebögen zur Messung der KI-Readiness generiert?

Die vorliegende Untersuchung behandelt die **konzeptionelle und inhaltliche Itemqualität**. Eine empirische Überprüfung von Reliabilität, Faktorenstruktur oder Konstruktvalidität wurde **nicht** durchgeführt. Die Formulierung „valide Fragebögen“ in der Forschungsfrage wird daher als Zielanforderung verstanden, nicht als bereits nachgewiesenes Ergebnis.

## Methodischer Ansatz

Design Science Research nach Peffers et al. (2007). Das Artefakt ist ein vierphasiger Leitfaden:

1. Theoretische Konstruktexplikation und Prüfung der Quellendeckung
2. Facettenspezifische Itemgenerierung
3. LLM-gestützte Prüfung mit anschließender menschlicher Kontrolle und Revision
4. Kriteriengeleitete Evaluation und Dokumentation

Als Vergleichsbedingung dient ein einfacher Ausgangsprompt, der neun Items für drei vorgegebene Themenbereiche erzeugen soll.

## Quellen und Material

Die wissenschaftlichen Original-PDFs werden aus urheberrechtlichen Gründen nicht in diesem Repository bereitgestellt. Ihre bibliographischen Angaben und die tatsächlich in NotebookLM verwendeten Dokumente müssen in der Hausarbeit und in einem ergänzenden Quellenverzeichnis angegeben werden.

Besonders einschlägig:

- Do Khac, L. T., Leyer, M., Wichmann, J., & Richter, A. (2025). Divisional perspectives on trust in generative AI: An empirical study of senior decision-makers. *Enterprise Information Systems*. https://doi.org/10.1080/17517575.2025.2481557
- Boateng, G. O., et al. (2018). Best practices for developing and validating scales for health, social, and behavioral research: A primer. *Frontiers in Public Health, 6*, 149. https://doi.org/10.3389/fpubh.2018.00149
- Peffers, K., et al. (2007). A design science research methodology for information systems research. *Journal of Management Information Systems, 24*(3), 45–77. https://doi.org/10.2753/MIS0742-1222240302

## NotebookLM-Ausgaben

Unter `notebooklm_outputs/` sind die fünf exportierten NotebookLM-Ausgaben als **Texttranskripte der bereitgestellten PDFs** dokumentiert. Die Inhalte wurden aus den PDFs ausgelesen; das ursprüngliche Seitenlayout und anklickbare interne Quellenmarker können dabei verloren gehen. Die fünf Original-PDFs werden von der Verfasserin separat aufbewahrt.

**Wichtiger Transparenzhinweis (Stand: erster Durchlauf):** Die als „Phase 2 – Itemgenerierung“ exportierte PDF enthält erneut die Konstruktexplikation aus Phase 1 und **keinen eigenständigen Itempool**. Die anschließende Itemprüfung bezieht sich erkennbar auf die neun Items der Ausgangsbedingung. Ein vollständiger unabhängiger A/B-Vergleich ist damit in diesem Durchlauf nicht möglich. Die Revisionen sind als iterative Überarbeitung eines Ausgangspools zu interpretieren. Der Dateiname ist keine Behauptung über die tatsächlich abgeschlossene Aktivität.

Eine korrigierte Generierung kann mit `prompts/phase2_korrektur.txt` in einem getrennten Notebook mit identischem Quellenkorpus durchgeführt und anschließend mit Datum, Modell-/Werkzeugangaben und vollständigem Output ergänzt werden. Die PDF-Originale des ersten Durchlaufs sind zusätzlich im separat bereitgestellten Archiv verfügbar, aber nicht als Binärdateien in diesem Repository gespeichert.

## Bewertung

Die Prüfung verwendet fünf vorab definierte Kriterien:

1. Theoretische Passung und nachprüfbarer Quellenbezug
2. Eindeutigkeit / Vermeidung doppelläufiger Fragen
3. Verständlichkeit
4. Redundanzfreiheit
5. Formale Kompatibilität mit der siebenstufigen Zustimmungsskala

Zusätzlich wird auf Pool-Ebene die Abdeckung aller theoretisch begründeten Facetten bewertet. Ein Bewertungsraster und die vorläufigen Beobachtungen befinden sich in `evaluation.md`.

## Limitationen

- Ein einzelner dokumentierter Durchlauf und ein kleiner Itempool von neun Aussagen erlauben keine Generalisierung.
- Phase 3 ist eine LLM-Selbstprüfung und keine unabhängige psychometrische Expertenbegutachtung.
- Theoretische Konzepte wie Einstellung, Vertrauen, Kompetenz und organisationale Bedingungen dürfen nicht ungeprüft zu einer einheitlichen Skala zusammengezogen werden.
- Quellenmarker aus NotebookLM-Exporten (z. B. „1“, „2“) sind ohne aufgelöste Quellstellen keine vollständigen wissenschaftlichen Literaturbelege.
- Keine Befragung, kein kognitiver Pretest und keine statistische Skalenvalidierung.

## Reproduzierbarkeit

Für eine Reproduktion sind dieselben Quelledateien, Prompttexte, die gewählte Quellenauswahl, die NotebookLM-Version beziehungsweise das Nutzungsdatum, die Reihenfolge der Prompts sowie die unbearbeiteten Antworten erforderlich. Exakte Reproduktion der LLM-Ausgaben ist selbst bei gleichem Prompt nicht garantiert.

## NotebookLM-Link

**Noch ergänzen:** Freigabelink zur prüfbaren Chat-/Notebookansicht. Vor Freigabe prüfen, welche hochgeladenen Quellen Dritte sehen können und ob deren Weitergabe zulässig ist.
