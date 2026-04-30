# UC-03d: Diagnoseunterstützung (CT / Röntgen / Behandlungspfade)
> Fallstudie KI-Beauftragter

---

## Szenario

Das Krankenhaus St. Ulrich führt seit sechs Monaten ein KI-System zur automatisierten Auswertung von CT- und Röntgenbildern ein. Der Pilot in der Radiologie läuft, der komplette Roll-Out über alle in Frage kommenden Abteilungen ist für das nächste Quartal geplant. Das System erkennt Muster, identifiziert Auffälligkeiten und priorisiert Behandlungspfade für das medizinische Personal. Es gibt eine Schnittstelle zu einer in Indien von einem dortigen Dienstleister gehosteten Datenbank mit über 10 Mio. anonymisierten CTs, insbesondere aus dem Gebiet der Onkologie. Diese Schnittstelle ist noch nicht aktiviert; der Chefarzt der Onkologie ist jedoch ein Befürworter, dies zu tun, da er auf einem Kongress von den diagnostischen Erfolgen des Werkzeugs gehört hat.

Eine DSFA wurde vor Pilotbeginn vom externen DSB durchgeführt — beschränkt auf den Pilotbetrieb in der Radiologie. Für den Voll-Roll-Out ist sie noch nicht aktualisiert. Die Aktivierung der Indien-Datenbank wurde explizit nicht abgedeckt.

Es ist vorgesehen, dass ein Radiologe jede Ausgabe des Systems prüft und die (Vor-)Diagnose verifiziert ("Ist das Ergebnis klinisch plausibel?"). In der Pilotphase zeigt sich: Bei hoher Arbeitsbelastung neigen einige Ärzte dazu, Routinebefunde nur kurz zu überfliegen. Die Trefferquote des Systems ist hoch — das verstärkt die Tendenz, die Aussagen der KI nicht zu hinterfragen.

Das System wurde von einem externen Softwarehaus entwickelt. Das Krankenhaus ist Betreiber und muss das System laufend validieren ("Wird richtig diagnostoziert?"). Es wurde ein Wartungsvertrag abgeschlossen — der Anbieter ist verpflichtet, das Modell aktuell zu halten. Der Anbieter ist nach ISO 13485 zertifiziert (Medizinprodukte-QMS) und hat die Konformitätsbewertung nach AI Act Anhang VI durchgeführt. CE-Kennzeichnung liegt vor. Eine ISO-42001-Zertifizierung ist nicht angestrebt — der Anbieter argumentiert, dass 13485 plus AI Act-Konformität ausreicht. Der Anbieter hat im Pilotzeitraum bereits zwei Modell-Updates eingespielt. Die Frage, ab wann ein Update als "wesentliche Änderung" gilt und neu konformitätsbewertet werden müsste, ist vertraglich (noch) nicht geklärt.

Die Patientenaufklärung über KI-Beteiligung ist gegenwärtig auf eine Zeile im allgemeinen Behandlungsvertrag reduziert. DSB und Ärztevertreter streiten, ob das ausreicht. Der Personalrat hat die Pilotphase mitgetragen, äußert aber Sorgen, dass beim Roll-Out die Verantwortung zunehmend bei den Ärzten verbleibt, während das Tempo durch die KI-Vorgabe steigt.

**Achtung:** Die gegenwärtige Situation in Krankenhäusern: Längere Wartezeiten führen dazu, dass Patienten kränker werden, wenn sie endlich behandelt werden. Das bedeutet: Die Qualität der Trainingsdaten spiegelt eine durch den Doom Loop verzerrte Realität wider.

---

## Lernziele

- Ein Hochrisiko-KI-System nach Anhang III Nr. 5 EU AI Act vollständig einordnen
- Betreiberpflichten nach Art. 26 EU AI Act für ein Hochrisiko-System benennen
- Bias-Risiken bei medizinischen KI-Systemen erkennen und einschätzen
- Post-Market-Monitoring-Anforderungen nach Art. 72 EU AI Act anwenden
- Den Zusammenhang zwischen Trainingsdaten-Qualität und Systemgerechtigkeit (Turing Institute) erläutern

---

## Weiterführende Quellen

- EU AI Act Anhang III Nr. 5: https://artificialintelligenceact.eu/
- EU AI Act Art. 14 (Human Oversight): https://artificialintelligenceact.eu/article/14/
- EU AI Act Art. 72 (Post-Market-Monitoring): https://artificialintelligenceact.eu/article/72/
- Turing Institute — AI Ethics: https://doi.org/10.5281/zenodo.3240529
- DSGVO Art. 9 (Gesundheitsdaten): https://gdpr-info.eu/art-9-gdpr/
