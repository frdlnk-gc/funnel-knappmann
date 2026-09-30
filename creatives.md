# KNAPPMANN – Creatives & Copies (25.09.2026, manuell von Freddy beauftragt)

Stelle: Facharbeiter GaLaBau (m/w/d) · Arbeitsort: 45356 Essen (Heinz-Bäcker-Straße 31, laut Anzeige „Projekte in Essen und Umgebung“)
Tarif: Premium · Laufzeit 30 Tage (Freddy-Vorgabe) · direkt live geschaltet · Targeting: 30 km um 45356 Essen
Anzeigengruppe: KNAPPMANN +30km (120255037305660063), 20 €/Tag, Ende 25.10.2026

## Creatives (alle deterministisch per PIL gesetzt, 0 € API)
1. creative-1-karten-hook – karten_hook_creative.py (karten-hook-creative.json): FACHARBEITER GALABAU (m/w/d), Pille „Ohne Lebenslauf & Anschreiben!“, Foto-Kachel Mitarbeiter am Firmenwagen, Karte Essen
2. creative-2-collage – collage_creative.py (collage-creative.json): Duo mit Vermessungsgerät / Minibagger / Dreier-Team, CTA-Fläche Markengrün
3. creative-3-wir-suchen – split_creative.py panel top (grünes Panel #279D2F): „WIR SUCHEN IN ESSEN & UMGEBUNG“, Subline „Unbefristet, in Vollzeit – mit modernem Maschinenpark.“, Teamfoto vor dem Bagger
4. creative-4-checkliste – split_creative.py panel bottom (weiß): Unbefristeter Arbeitsvertrag · Moderner Maschinenpark · Jobrad-Leasing

Bildregel geprüft: Gesichter sichtbar, Menschen zentral, nichts über Personen. Erste Collage-Fassung hatte rechts oben einen halb angeschnittenen Kopf → Foto getauscht. LP-Galerie ohne Rückenansichten (job-02 Entwässerung, job-01 Pflasterfläche aussortiert).

## Belege (API api/slugs/search/vollzeit-facharbeiter-galabau-unbefristet-in-essen-2)
- Vollzeit, unbefristet: working_time „Vollzeit“, employment_type „Unbefristet“, Benefit „Unbefristeter Arbeitsvertrag“
- „modernem Maschinenpark, starkem Teamgeist und sicheren Perspektiven“ – description
- „setzen wir dich nach deinen Stärken ein – im Landschaftsbau oder in der Begrünung“, „Unsere Karriereleiter bietet dir klare Entwicklungsmöglichkeiten“ – description
- „Wer das macht, was ihm liegt, macht es auch richtig gut.“ – description (wörtlich)
- Benefits-Tab: Flache Hierarchien, Freundliches Arbeitsklima, Interne Karrierechancen, Jobrad-Leasing, Unbefristeter Arbeitsvertrag (alle is_displayed)
- 190 Mitarbeitende (number_of_employees + employer.description), gegründet 1960 (founding_year, „Seit 1960 gestalten wir Lebensräume“), Familienunternehmen – employer.description
- Aufgaben: your_tasks (6 Punkte); your_profile wiederholt die ersten 3 Aufgaben, keine Ausbildungsforderung
- Kein Gehalt in der Anzeige → nirgends eine Zahl
- Umkreis-Städte (Copy A, Creatives): Gelsenkirchen, Oberhausen, Bottrop – Nachbarstädte von Essen-Vogelheim, alle im 30-km-Kreis

## Copy A
Facharbeiter GaLaBau (m/w/d) in Essen gesucht – ideal, wenn du in Gelsenkirchen, Oberhausen, Bottrop oder Umgebung wohnst.
Erdbau, Wegebau, Entwässerung und Pflanzarbeiten: Bei KNAPPMANN arbeitest du an vielseitigen Landschaftsbau-Projekten in Essen und Umgebung – mit modernem Maschinenpark und starkem Teamgeist.

Damit sind dir sicher:
✔ Unbefristeter Arbeitsvertrag in Vollzeit
✔ Einsatz nach deinen Stärken – Landschaftsbau oder Begrünung
✔ Klare Karriereleiter & interne Karrierechancen
✔ Jobrad-Leasing

In 60 Sekunden angefragt – ohne Lebenslauf & Anschreiben.

Überschrift: Unverbindliches Job-Angebot sichern
Beschreibung: In 60 Sek. – ohne Lebenslauf

## Copy B
Du kannst Pflaster, Erdbau und Entwässerung – und willst dort arbeiten, wo man deine Stärken sieht?
KNAPPMANN in Essen sucht einen Facharbeiter GaLaBau (m/w/d). Seit 1960 gestaltet das Familienunternehmen Lebensräume – von großen Parkanlagen bis zu anspruchsvollen Tiefbauprojekten. 190 Mitarbeitende ziehen hier an einem Strang.

„Wer das macht, was ihm liegt, macht es auch richtig gut.“

Unbefristet, flache Hierarchien, freundliches Arbeitsklima – hol dir jetzt dein unverbindliches Job-Angebot.

Überschrift: Dein Job bei KNAPPMANN in Essen
Beschreibung: 100 % unverbindlich & diskret

---

# Zweiter Standort: Rommerskirchen (30.09.2026, Vorgabe Freddy/Jana)

Kunde sucht dieselbe Stelle zusätzlich am Standort Rommerskirchen (Prio 1 laut Jana). Aufteilung: 1 Kampagne, 2 Anzeigengruppen à 10 €/Tag – „KNAPPMANN Essen +30km" und „KNAPPMANN Rommerskirchen +30km" (30 km um Grevenbroicher Str. 31, 41569 Rommerskirchen), Laufzeit wie Essen bis 25.10.2026.

- Funnel: eigene Seite https://knappmann.green-careers.de/rommerskirchen/ (Kopie der Essen-Seite, Badge/Titel/Karte Rommerskirchen). Leads gehen in denselben Tab „14 KNAPPMANN"; Standort steht im Feld „stelle" („… – Standort Rommerskirchen" bzw. „… – Standort Essen"), das in der Sheet-Spalte und in der Bestätigungsmail erscheint. „quelle" bleibt die Root-URL, weil die Bestätigungsmail das Logo von quelle/logo-mail.png lädt.
- Creatives: creatives-rommerskirchen/ – die 4 Essen-Creatives mit Ortszeile „Rommerskirchen · Grevenbroich · Neuss", Kicker „WIR SUCHEN IN ROMMERSKIRCHEN & UMGEBUNG", Creative 1 mit Karte Rommerskirchen (OSM Zoom 10, img/karte-rommerskirchen.jpg).
- Titel bleibt „Facharbeiter GaLaBau (m/w/d)" (laut Jana dieselbe Stelle; die Portal-Anzeige Rommerskirchen heißt „Landschaftsgärtner").
- Belege Rommerskirchen (API api/slugs/search/vollzeit-landschaftsgartner-unbefristet-in-rommerskirchen): gleiche Aufgaben wie Essen; Benefits u. a. Unbefristeter Arbeitsvertrag, Jahresprämie, Jobrad-Leasing, Vermögenswirksame Leistungen, Anhängerführerschein Kostenübernahme, Keine Montageeinsätze mit Übernachtung, Flache Hierarchien, Freundliches Arbeitsklima.
- Umkreis-Orte (plz_geo, km zum Standort): Grevenbroich 6, Bergheim 8, Dormagen 11, Neuss 13.

## Copy A (Rommerskirchen)
Facharbeiter GaLaBau (m/w/d) in Rommerskirchen gesucht – ideal, wenn du in Grevenbroich, Neuss, Dormagen, Bergheim oder Umgebung wohnst.
Erdbau, Wegebau, Entwässerung und Pflanzarbeiten: Bei KNAPPMANN arbeitest du an anspruchsvollen Landschaftsbau-Projekten im Rheinland – mit modernem Maschinenpark und starkem Teamgeist.

Damit sind dir sicher:
✔ Unbefristeter Arbeitsvertrag in Vollzeit
✔ Jahresprämie, Jobrad-Leasing & vermögenswirksame Leistungen
✔ Kostenübernahme für den Anhängerführerschein
✔ Keine Montageeinsätze mit Übernachtung

In 60 Sekunden angefragt – ohne Lebenslauf & Anschreiben.

Überschrift: Unverbindliches Job-Angebot sichern
Beschreibung: In 60 Sek. – ohne Lebenslauf

## Copy B (Rommerskirchen)
Du kannst Pflaster, Erdbau und Entwässerung – und willst dort arbeiten, wo man deine Stärken sieht?
KNAPPMANN in Rommerskirchen sucht einen Facharbeiter GaLaBau (m/w/d). Seit 1960 gestaltet das Familienunternehmen Lebensräume – von großen Parkanlagen bis zu anspruchsvollen Tiefbauprojekten. 190 Mitarbeitende ziehen hier an einem Strang.

„Wer das macht, was ihm liegt, macht es auch richtig gut.“

Unbefristet, flache Hierarchien, freundliches Arbeitsklima – hol dir jetzt dein unverbindliches Job-Angebot.

Überschrift: Dein Job bei KNAPPMANN in Rommerskirchen
Beschreibung: 100 % unverbindlich & diskret
