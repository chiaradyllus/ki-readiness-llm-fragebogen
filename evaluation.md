# Auswertungsnotizen zum ersten NotebookLM-Durchlauf

## Dokumentierte Reihenfolge

| Schritt | Beobachtbarer Output | Status |
|---|---|---|
| A: Ausgangsprompt | Neun Items, je drei für KI-Kompetenz, Einstellung/Vertrauen und organisationale Unterstützung | Vorhanden |
| 1: Konstruktexplikation | Quellenbezogene theoretische Abgrenzung; organisatorische Unterstützung als uneinheitlich erkannt | Vorhanden |
| 2: Itemgenerierung | PDF wiederholt die Konstruktexplikation und erzeugt keine neun neuen Items | **Fehlt im vorliegenden Export** |
| 3: Itemprüfung | Prüft die neun Ausgangsitems und schlägt bei allen neun Revisionen vor | Vorhanden, aber nicht unabhängig von A |
| 4: Dokumentation | Dokumentiert den revidierten Ausgangspool und theoretische Einschränkungen | Vorhanden |

## Beobachtungen auf Itemebene

| Item | Ausgangsproblem | Änderung in der LLM-Revision | Offene Kritik |
|---|---|---|---|
| 1 Kompetenz | Breiter Bezugsrahmen „Arbeitsumfeld“ | Bezug auf eigene genutzte Anwendungen | Mitarbeitende ohne bisherige KI-Nutzung möglicherweise ausgeschlossen |
| 2 Kompetenz | „nachvollziehen und beurteilen“, „korrekt und verlässlich“ | Fokussierung auf inhaltliche Korrektheit | Selbsteinschätzung statt objektiver Kompetenz |
| 3 Kompetenz | „problemlos und eigenständig“ | Fokus auf eigenständige Bedienung | Nähe zu Selbstwirksamkeit statt zu objektivem Wissen |
| 4 Einstellung | „vorteilhaft und gewinnbringend“ | eine Nutzenbewertung | Einstellung und wahrgenommener Nutzen sind nicht identisch |
| 5 Vertrauen | Prozess- und Ergebnisvertrauen vermischt | Fokussierung auf zuverlässige Aufgabenausführung | Keine Messung von Risiko/Vulnerabilität |
| 6 Affekt | Aufgaben und Entscheidungen gekoppelt | nur Aufgabenunterstützung | Affekt und Vertrauen sollten theoretisch getrennt bleiben |
| 7 Unterstützung | Ressourcen, Schulungen und Werkzeuge | nur technische Werkzeuge | Schulungsdimension entfällt aus dem neun Items umfassenden Pool |
| 8 Soziale Norm | Führungskräfte und Kolleg:innen gemeinsam | „wichtige Personen“ als Sammelbegriff | Personenbezug weiterhin zusammengefasst |
| 9 Governance | Richtlinien, Rahmenbedingungen und Datenschutzbeispiele vermischt | Datenschutzrichtlinien | Organisationales Vorhandensein einer Regel ist nicht allein psychologische Readiness |

## Kriterienraster zur späteren unabhängigen Bewertung

Je Item 1 = erfüllt, 0 = nicht erfüllt, **NV = aufgrund fehlender Quellennachweise nicht verifizierbar**:

- Theoretische Passung: eindeutige Dimension und überprüfbarer Quellenbezug
- Eindeutigkeit: genau ein interpretierbarer Sachverhalt
- Verständlichkeit: klare, zielgruppengerechte Formulierung
- Redundanzfreiheit: keine starke Bedeutungsdopplung zu einem anderen Item desselben Pools
- Formale Konsistenz: Aussage sinnvoll mit 1–7 Zustimmung zu beantworten

Die theoretische Passung soll **nicht automatisch mit 0 bewertet werden**, wenn die Quellenangabe lediglich noch nicht aufgelöst ist. Solche Fälle sind als NV zu dokumentieren und nachzuprüfen. Keine Punktesumme aus einer unvollständig bewerteten Matrix berichten.

## Vorsicht bei Schlussfolgerungen

- Beobachtung: **neun von neun** Ausgangsitems wurden im NotebookLM-Revisionsschritt verändert.
- Beobachtung: Mindestens die Items **2, 3, 5, 6, 7 und 8** wurden wegen vermischter Teilaspekte bzw. Bezugsgruppen kritisch angesprochen; daneben wurden Redundanzen und unscharfe Formulierungen identifiziert.
- Diese Befunde belegen keine validierte Skala und keinen kausalen Qualitätsvorteil gegenüber einer getrennt erzeugten Leitlinienbedingung.
- Die Aussage in der NotebookLM-Dokumentation, eine „inhaltliche Validität“ sei sichergestellt, geht über die dokumentierte LLM-Selbstprüfung hinaus. Zutreffend ist: Es wurden **indikative Kriterien für inhaltliche Qualität** geprüft.

## Nachzutragen

- Exakte Quellenliste des verwendeten NotebookLM-Notebooks
- Nutzungsdatum, identische Quellenauswahl und Plattformangaben
- Korrigierter eigenständiger Itempool aus Phase 2, falls ein A/B-Vergleich beabsichtigt ist
- Menschliche Prüfung der finalen Items mit vollständiger kriterienspezifischer Matrix
- Eventuell gemessene Bearbeitungszeiten; nicht nachträglich schätzen
