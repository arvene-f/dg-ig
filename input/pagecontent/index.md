<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

In einer Hausarztpraxis erfasst die behandelnde Ärztin eine bestätigte Arzneimittelallergie einer Patientin im elektronischen Patientendossier. Bei einer späteren Behandlung, beispielsweise auf einer Notfallstation, können medizinische Fachpersonen diese Information einsehen. Dadurch sollen allergische Reaktionen bei der Verordnung und Verabreichung von Medikamenten vermieden werden.

### Scope

Dieser Implementation Guide beschreibt die strukturierte Erfassung und den Austausch von Arzneimittelallergien auf Basis von HL7 FHIR und CH Core. Er berücksichtigt unter anderem den klinischen Status, den Allergiecode, die Kritikalität, den Beginn, die erfassende Person und mögliche Reaktionen.

Nicht abgedeckt sind Lebensmittel- und Umweltallergien, die Diagnostik von Allergien sowie konkrete Behandlungsempfehlungen.

### Artefakte

- [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Das FHIR-Profil definiert die Anforderungen an die strukturierte Dokumentation von Arzneimittelallergien.
- [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Das Beispiel zeigt eine bestätigte Penicillinallergie mit dokumentierter Hautreaktion und der erfassenden Ärztin.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Arvene Foniqi

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
