 # Lifestyle and Health Risk Prediction Dataset: von Kaggle
 [Zu Kaggle](https://www.kaggle.com/datasets/miadul/lifestyle-and-health-risk-prediction)

## 1. Datensatzbeschreibung
* **Titel und Quelle**

 * Titel: Lifestyle and Health Risk Prediction

 * Quelle: Kaggle (Hochgeladen von Miadul)

 * Ursprung: Synthetisch generierter Datensatz zur Simulation realer Lifestyle- und Wellness-Daten.

* **Struktur und Größe**

| Merkmal | Wert | Anmerkungen |
| :--- | :--- | :--- |
| **Format** | .csv | Standardisiertes, maschinenlesbares Format. |
| **Zeilenanzahl** | 5.000 | Größe des Datensatzes. |
| **Spaltenanzahl** | 12 | Anzahl der Features und Zielvariablen. |
| **Wichtige Spalte** | `health_risk` | Zielvariable (Target); kategorisch (`low`, `high`). |

* **Abdeckung und Lizenz**

 * Zeitliche Abdeckung: Nicht spezifisch.

 * Geografische Abdeckung: Keine explizite Angabe.

 * Lizenz: Die Wiederverwendung ist maximal erlaubt, da es sich um synthetische Daten handelt.

* **Basis-Statistiken**

 * Alter (age): Range von 18 bis 79 Jahren.

 * Schlaf (sleep): Range von ca. 3 bis 10 Stunden pro Nacht.

 * Lifestyle-Faktoren: Kategorische Variablen wie exercise (Sport: none, low, medium, high) und sugar_intake (Zuckerkonsum: low, medium, high).

## 2. Augmentierung des Datensatzes

Dieser Datensatz ist auf individueller Ebene detailliert, es fehlen ihm jedoch sozioökonomische Faktoren und ein geografischer Kontext.

**Augmentierungs-Datensatz**

 * Datenquelle: Daten zu Social Determinants of Health (SDOH), zum Beispiel von der WHO oder nationalen Statistikämtern.

 * Inhalt: Aggregierte Kennzahlen wie durchschnittliches Einkommen nach Beruf und berufsspezifische Stresslevel.

**Verknüpfung und Forschungsfragen**

 * Verknüpfungsschlüssel: Die Spalte profession dient als Schlüssel, um individuelle Profile mit den aggregierten Berufsgruppendaten zu verknüpfen.

## FAIR-Bewertung des Datensatzes

| Prinzip | Bewertung | Begründung |
| :--- | :--- | :--- |
| **Findable** (Auffindbar) | Gut | Leicht auffindbar auf Kaggle mit ausreichenden Metadaten. |
| **Accessible** (Zugänglich) | Sehr Gut | Direkt als CSV-Datei herunterladbar, keine Zugangsbarrieren. |
| **Interoperable** (Interoperabel) | Gut | Standardisiertes CSV-Format und klare englische Spaltennamen. |
| **Reusable** (Wiederverwendbar) | Sehr Gut | Offene CC0-Lizenz und thematisch konsistente Spaltenbezeichnungen. |
