
## Überblick:
# Zweite Harmonische Erzeugung (SHG)

**Konzept:** Bei der zweiten Harmonischen (SHG) verschmelzen zwei Photonen derselben Frequenz ω in einem nichtlinearen Medium zu einem einzigen Photon mit doppelter Frequenz (2ω). Anders gesagt entsteht Licht bei doppelter Frequenz (halbe Wellenlänge) des Anregungslichts. Mathematisch kann man sich das so vorstellen: Die Polarisation P im Medium enthält neben dem linearen Anteil (χ^(1)E) auch einen quadratischen Term χ^(2)E², der bei sinusförmischer Anregung zum Frequenzverdoppler führt. Anschaulich entspricht dies einem Dipol (z.B. einem Elektron im Atom), der in einem leichten, aber anharmonischen Potential liegt. Trifft ein sinusförmales E‑Feld ein, so beschreibt die resultierende Bewegung des Elektrons keine reine Sinusschwingung mehr, sondern enthält auch Oberwellen bei 2ω.

_Bild: Schematische Darstellung von SHG – zwei eingehende Wellen bei ω im **nichtlinearen Kristall** erzeugen eine Welle bei 2ω._ Dieses Bild verdeutlicht, wie im Kristall ein (hier vereinfachtes) zweites Feld mit doppelter Frequenz entsteht (jede Welle im Kristall kann man als oszillierendes Dipolmoment interpretieren). Entscheidend ist, dass das Material eine **nichtlineare Suszeptibilität χ^(2)** besitzt. In Medien mit Inversionssymmetrie (z.B. viele glaskristalline Festkörper) verschwindet χ^(2) im Dipolterm, sodass dort keine SHG möglich ist. Nur in **nicht-zentrosymmetrischen Kristallen** (z.B. ferroelectric materials) kann also ein Zweitharmonischer entstehen.

**Grundlagen:** Die Effizienz von SHG hängt stark von der **Phasenanpassung** ab. Wegen Dispersion haben Pump- und Zweitharmonische in einem Kristall unterschiedliche Phasengeschwindigkeiten. Nur wenn die Phasenrelation konstant bleibt (Phase Matching), addieren sich die Zweitharmonischen konstruktiv, andernfalls löschen sie sich wieder aus. Durch geeignete Kristallorientierung oder Temperaturwahl lässt sich dies kompensieren. Ein bekanntes Beispiel ist LBO-Kristall (Lithium­triborat), der bei ca. 25 °C perfekt für 1200–1400 nm pumplicht phasenangepasst ist – für 1064 nm muss man ihn auf etwa 200 °C erhitzen. Man spricht hier von **nichtkritischer Phasenanpassung** (d.h. keine Drehung des Kristalls nötig). Alternativ kann man die Kristallstruktur periodisch umpolen: Bei **PPLN** (periodisch gepoltes LiNbO₃) kehren sich die Kristallachsen regelmäßig um, sodass trotz Dispersion über lange Strecken konstruktive Überlagerung möglich wird. Unter optimaler Phasenanpassung kann SHG sehr effizient werden – in Laboraufbauten mit intensiven Laserpulsen erreicht man je nach Bedingungen konversionen von einigen % bis nahezu 100 %.

## Typische nichtlineare Kristalle

- **BBO (Beta-BaB₂O₄):** Weiter Transparenzbereich (UV bis Nah-IR), hohe Schadensgrenze. Häufig genutzt zur Verdopplung von Titan:Saphir-, Nd- und Yb-Laserstrahlen. Beispielsweise erzeugt man damit aus 800–1064 nm Pumplicht grünes bzw. violettes SHG-Licht.
    
- **LBO (LiB₃O₅ – Lithium­triborat):** Weitbandig transparent, sehr hohe Schadensschwelle, moderater χ^(2)-Wert[en.wikipedia.org](https://en.wikipedia.org/wiki/Lithium_triborate#:~:text=Lithium%20triborate%20%28LiB_,cooled%20depending%20on%20the%20wavelength). Wird oft für 1064→532 nm SHG mit Nd:YAG-Lasern verwendet (sowohl kritisch als auch nichtkritisch phasenangepasst)[en.wikipedia.org](https://en.wikipedia.org/wiki/Lithium_triborate#:~:text=Lithium%20triborate%20%28LiB_,cooled%20depending%20on%20the%20wavelength). Aufgrund des geringen Walk-off und der hohen Schadensgrenze ist LBO besonders für Hochleistungspulse geeignet.
    
- **LiNbO₃ (Lithium­niobat):** Ferroelectricer Kristall mit großem χ^(2). In Wellenleitern oder als periodisch gepolte Version (PPLN) sehr beliebt, da man hier mittels Temperatur- oder Polungs­periodenabhängigkeit die Phasenanpassung feinjustieren kann. Durch die Ferroelektrizität (Permenant­polung) lässt sich LiNbO₃ elektro-optisch und nichtlinear besonders gut nutzen.
    
- **Weitere:** KTP (KTiOPO₄), KDP (Kaliumdihydrogenphosphat) u.v.m., jeweils mit eigenen Vor- und Nachteilen (Transparenzbereich, Schadensschwelle, Polungsfähigkeit). Insgesamt muss ein Kristall für SHG χ^(2)≠0 besitzen (also nicht-zentrosymmetrisch sein) und unter Phasen­anpassungsbedingungen betrieben werden.
    

## Anwendungen der SHG

- **Grüne Laser (Frequenzverdopplung):** Industrie und Forschung nutzen SHG, um aus Infrarot- oder Rotlicht grüne Wellenlängen zu erzeugen. Ein typisches Beispiel ist der Nd:YAG-Laser (λ=1064 nm), aus dem durch SHG ein 532 nm („grünes“) Laserlicht wird. Viele Laserpointer-Konstruktionen nutzen diesen Trick (dabei ist es wichtig, Infrarotanteile zu filtern, da 1064 nm für das Auge unsichtbar, aber gefährlich ist).
    
- **Ultraschnelle Laserpulse:** Zur Charakterisierung ultrakurzer Pulse (Autokorrelatoren, FROG-Methoden) wird SHG eingesetzt. Durch Koppelung zweier zeitversetzter Pulse in einem SHG-Kristall erhält man über die Intensität des resultierenden SHG-Signals Rückschluss auf die Pulsdauer. Auch hier gilt: Die SHG-Effizienz hängt quadratisch vom Input ab – daher eignet sie sich gut für die Messung sehr kurzer, intensiver Pulse.
    
- **SHG-Mikroskopie:** In der Biologie/Medizin nutzt man SHG als Kontrastmechanismus. Nur nicht-zentrosymmetrische Molekülstrukturen (z.B. Kollagenfasern im Gewebe) erzeugen SHG, sodass man diese gezielt abbilden kann. Mit Femtosekundenlasern erreicht man extrem hohe laterale und axiale Auflösung (vergleichbar mit Konfokalmikroskopen) ohne Fluoreszenzmarker. Beispiel: SHG-Bildgebung des Hornhautgewebes oder anderer kollagenreicher Strukturen liefert kontrastreiche Bilder allein durch die 2ω‑Emission.
    
- **Materialcharakterisierung:** SHG ist ein schneller Test für Nicht-Zentrosymmetrie in Kristallen. In einem Kurtz-Perry-Apparat zermahlenes Material wird mit einem Laser gepulst – ist das Material nicht-zentrosymmetrisch, tritt SHG auf. Damit lassen sich Raumgruppen klären und Phasenübergänge beobachten. Da nur ~22 % aller natürlichen Kristalle keine Inversionssymmetrie haben, ist die Entdeckung eines SHG-Signals schon sehr aussagekräftig. SHG/Mikroskopie dient heute auch zur Analyse von Nanomaterialien, Grenzflächen oder neuartigen Halbleitern (z.B. zur Untersuchung von zweidimensionalen Perowskit-Schichten auf lokale Symmetriebrüche).
    

## Technische Relevanz und Ausblick

SHG ist in der angewandten Optik hochrelevant: Die Möglichkeit, Laserfrequenzen gezielt zu verdoppeln, erweitert das Spektrum verfügbarer Wellenlängen (z.B. beim Bau kompakter Visible-Laser aus Infrarot­quellen). Nichtlineare Spektroskopie (SHG/THG) liefert Einblicke in Materialeigenschaften, da etwa das Auftreten eines 2ω‑Signals sofort auf gebrochene Inversionssymmetrie hinweist. In der aktuellen Forschung werden Perowskit-Materialien mittels SHG und Drittharmonischer (THG) Spektroskopie untersucht, um kristalline Anisotropien und Ladungsträger-Dynamik aufzuklären.

**Wichtige Punkte im Überblick:**

- In einem SHG-Prozess verschmelzen _zwei_ Photonen (ω) zu einem Photon mit _doppelter_ Frequenz (2ω).
    
- Vorausetzung ist ein nicht-zentrosymmetrischer Kristall mit χ^(2)≠0.
    
- Die Polarisationsantwort enthält einen Term P(2ω)∝χ^(2)E(ω)², der die Verdopplung ermöglicht.
    
- Phasenanpassung (z.B. Winkel- oder Temperaturabstimmung, periodische Polung) ist nötig für hohe Effizienz.
    
- Typische SHG-Kristalle sind LiNbO₃ (PPLN), LBO, BBO u.a., genutzt in Lasern und Spektroskopie [en.wikipedia.org](https://en.wikipedia.org/wiki/Lithium_triborate#:~:text=Lithium%20triborate%20%28LiB_,cooled%20depending%20on%20the%20wavelength).
    
- Anwendungen reichen von grünen Laserpointern über nichtlineare Mikroskopie bis zur Charakterisierung von Kristallen und Nanostrukturen.
    

**Quellen:** Einführung und Prinzipien nach gängigen Physik-Quellen und Lehrbüchern; Anwendungen und Materialien nach Fachliteratur und Wikipedia





_____
# Second & Third Harmonic Generation - Präsentationsstruktur (20 Min)

## Zeitaufteilung und Folienverteilung
- **Gesamtzeit:** 20 Minuten
- **Gesamtfolien:** ~15-18 Folien
- **Zeitpuffer:** 2-3 Minuten für Fragen/Diskussion

---

## 1. Einführung und Motivation (3 Min, 2-3 Folien)

### Folie 1: Titel und Überblick
**Inhalt der Folie:**
- Titel: "Second & Third Harmonic Generation in der nichtlinearen Optik"
- Kurzer Überblick über die Agenda
- Motivation: Warum ist Frequenzkonversion wichtig?

**Zu vermitteln:**
- Anwendungen in der Praxis (Laserfrequenzverdopplung, Mikroskopie)
- Grundlage für viele moderne optische Technologien

### Folie 2: Was ist nichtlineare Optik?
**Inhalt der Folie:**
- Vergleich: Lineare vs. nichtlineare Optik
- Einfache Grafik: E-Feld → P (Polarisation)
- Lineare Optik: P ∝ E
- Nichtlineare Optik: P ∝ E + χ⁽²⁾E² + χ⁽³⁾E³ + ...

**Zu vermitteln:**
- Bei hohen Lichtintensitäten wird die Materialantwort nichtlinear
- Neue Phänomene entstehen: Frequenzmischung, Harmonische Generation

---

## 2. Grundlagen der harmonischen Generation (4 Min, 3-4 Folien)

### Folie 3: Energieerhaltung und Photonenprozesse
**Inhalt der Folie:**
- Schematische Darstellung der Photonenprozesse
- SHG: 2 Photonen (ω) → 1 Photon (2ω)
- THG: 3 Photonen (ω) → 1 Photon (3ω)
- Energieerhaltung: n·ℏω = ℏ(n·ω)

**Zu vermitteln:**
- Multiphotonenprozesse erfordern hohe Intensitäten
- Wahrscheinlichkeit nimmt mit der Ordnung ab
- Nicht-zentrosymmetrische Materialien für gerade Ordnungen nötig

### Folie 4: Nichtlineare Suszeptibilität
**Inhalt der Folie:**
- χ⁽²⁾ für SHG (Second-order nonlinear susceptibility)
- χ⁽³⁾ für THG (Third-order nonlinear susceptibility)
- Materialanforderungen für beide Prozesse

**Zu vermitteln:**
- SHG: Benötigt non-zentrosymmetrische Kristalle
- THG: Möglich in allen Materialien (auch Flüssigkeiten)
- Größenordnungen der Suszeptibilitäten

### Folie 5: Phasenanpassung (Phase Matching)
**Inhalt der Folie:**
- Impulserhaltung: Δk = k₂ω - 2k_ω = 0
- Grafische Darstellung des Phase-Matching
- Kritische vs. nichtkritische Phasenanpassung

**Zu vermitteln:**
- Ohne Phasenanpassung: destruktive Interferenz
- Verschiedene Techniken: Winkelanpassung, Temperaturanpassung
- Effizienz hängt stark von Phase-Matching ab

---

## 3. Second Harmonic Generation (SHG) (6 Min, 4-5 Folien)

### Folie 6: SHG - Grundprinzip
**Inhalt der Folie:**
- Prozessschema: ω + ω → 2ω
- Typische Konversionseffizienzen
- Anwendungsbeispiele (grüne Laserpointer, UV-Erzeugung)

**Zu vermitteln:**
- Frequenzverdopplung ist der häufigste nichtlineare Prozess
- Kommerzielle Bedeutung
- Typische Materialien: BBO, KDP, LiIO₃

### Folie 7: Mathematische Beschreibung
**Inhalt der Folie:**
- Wellengleichung für SHG
- Kopplungsgleichungen (vereinfacht)
- Abhängigkeit von Kristalllänge und Intensität

**Zu vermitteln:**
- Quadratische Abhängigkeit von der Eingangsintensität
- Sättigungseffekte bei hohen Intensitäten
- Optimale Kristalllänge existiert

### Folie 8: SHG in Resonatoren (Cavity SHG)
**Inhalt der Folie:**
- Verstärkung durch Resonatorüberhöhung
- Doppelt resonante Kavitäten
- Hopf-Bifurkation und Instabilitäten

**Zu vermitteln:**
- Resonatoren erhöhen die Effizienz drastisch
- Neue Dynamik: Oszillationen, Chaos möglich
- Praktische Vorteile: niedrigere Schwellleistung

### Folie 9: SHG Materialien und Anwendungen
**Inhalt der Folie:**
- Wichtige Kristalle: BBO, KDP, LiIO₃, KTP
- Anwendungen: Laserfrequenzverdopplung, Mikroskopie
- Praktische Herausforderungen

**Zu vermitteln:**
- Materialauswahl abhängig von Wellenlänge und Leistung
- SHG-Mikroskopie: Label-freie Bildgebung
- Schädigungsschwellen und thermische Effekte

---

## 4. Third Harmonic Generation (THG) (4 Min, 3-4 Folien)

### Folie 10: THG - Grundprinzip
**Inhalt der Folie:**
- Prozessschema: ω + ω + ω → 3ω
- Vergleich zu SHG: Volumen- vs. Oberflächenprozess
- Materialanforderungen

**Zu vermitteln:**
- THG ist ein Volumenprozess (im Gegensatz zu SHG)
- Möglichkeit in zentrosymmetrischen Materialien
- Verstärkung an Grenzflächen

### Folie 11: THG Eigenschaften und Unterschiede zu SHG
**Inhalt der Folie:**
- Kubische Intensitätsabhängigkeit
- Phasenanpassung schwieriger
- Typische Effizienzen (niedriger als SHG)

**Zu vermitteln:**
- Stärkere Intensitätsabhängigkeit → höhere Schwellwerte
- Oft schlechtere Konversionseffizienz
- Besondere Bedeutung für kurze Pulse

### Folie 12: THG in Flüssigkeiten und Mikroskopie
**Inhalt der Folie:**
- THG in Flüssigkeiten (einzigartig unter harmonischen Prozessen)
- Mikroskopie-Anwendungen
- Materialien: BBO, Membrane

**Zu vermitteln:**
- Einzige harmonische Generation in Flüssigkeiten
- Wichtig für biologische Mikroskopie
- Komplementäre Information zu SHG-Mikroskopie

---

## 5. Vergleich und höhere Harmonische (2 Min, 2 Folien)

### Folie 13: SHG vs. THG - Direkter Vergleich
**Inhalt der Folie:**
- Tabelle: Effizienz, Materialien, Anwendungen
- Vor- und Nachteile beider Prozesse
- Wann welchen Prozess verwenden?

**Zu vermitteln:**
- SHG: höhere Effizienz, beschränkt auf non-zentrosymmetrische Materialien
- THG: universeller, aber weniger effizient
- Komplementäre Techniken

### Folie 14: Höhere Harmonische (4HG, 5HG, ...)
**Inhalt der Folie:**
- Fourth Harmonic Generation (4HG)
- Herausforderungen bei höheren Ordnungen
- High Harmonic Generation (HHG) als alternativer Prozess

**Zu vermitteln:**
- Mit steigender Ordnung exponentiell abnehmende Effizienz
- Sehr hohe Intensitäten erforderlich
- HHG für extrem hohe Harmonische (andere Physik)

---

## 6. Zusammenfassung und Ausblick (1 Min, 1 Folie)

### Folie 15: Zusammenfassung
**Inhalt der Folie:**
- Kernpunkte: SHG und THG als wichtige nichtlineare Prozesse
- Anwendungsgebiete: Laser, Mikroskopie, Spektroskopie
- Zukunftsperspektiven

**Zu vermitteln:**
- Harmonische Generation ist Grundlage vieler moderner Technologien
- Aktive Forschungsgebiete: Nanophotonik, Quantenoptik
- Praktische Bedeutung wird weiter zunehmen

---

## Präsentationstipps:

### Visuelle Elemente:
- **Schematische Diagramme:** Photonenprozesse, Energielevel
- **Grafiken:** Phase-Matching, Konversionseffizienz vs. Parameter
- **Fotos:** Typische Aufbauten, Kristalle, Anwendungen
- **Animationen:** Wellenpakete, Frequenzkonversion (wenn möglich)

### Wichtige Gleichungen (minimal halten):
- P = χ⁽¹⁾E + χ⁽²⁾E² + χ⁽³⁾E³
- Phasenanpassung: Δk = 0
- Intensitätsabhängigkeit: I₂ω ∝ I²_ω, I₃ω ∝ I³_ω

### Diskussionspunkte für Fragen:
- Praktische Limitationen und Lösungsansätze
- Neue Entwicklungen in der harmonischen Generation
- Vergleich mit anderen nichtlinearen Prozessen

### Zeitmanagement:
- Strikt bei der Zeitaufteilung bleiben
- Komplexere mathematische Ableitungen nur oberflächlich
- Fokus auf physikalisches Verständnis und Anwendungen
- Beispiele aus der Praxis einbauen für besseres Verständnis