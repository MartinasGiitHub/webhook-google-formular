# Webhook → Google Sheet (Testdatenformular)

Dieses Projekt ist ein Demonstrator zur Automatisierung eines Datenflusses von HTML-Formularen via Webhook in ein Google Sheet. Ziel ist es, Eingabedaten (z. B. für Testzwecke) strukturiert zu erfassen, zu übertragen und weiterzuverarbeiten – ohne manuelle Zwischenschritte.

## 🔧 Projektüberblick

- **Frontend:** HTML-Formular (responsive, barrierearm, mit Pflichtfeld-Validierung)
- **Übertragung:** POST an n8n-Webhookschnittstelle (folgt)
- **Zielsystem:** Google Sheets (Service Account Integration in n8n)
- **Host:** GitHub Pages

## 📥 Eingabefelder

| Feld         | Typ     | Pflicht |
|--------------|---------|---------|
| Vorname      | Text    | ✅      |
| Nachname     | Text    | ✅      |
| E-Mail       | E-Mail  | ✅      |
| Stadt        | Text    | optional |
| PLZ          | Text    | optional |

## 🌐 Workflow-Ziel

1. Nutzer füllt Formular aus
2. Formular sendet Daten via Webhook an n8n
3. n8n verarbeitet, prüft und speichert die Daten in ein Google Sheet

## ✅ ToDos

- [x] HTML-Formular erstellen
- [ ] Webhook in n8n anlegen
- [ ] Google Sheet vorbereiten
- [ ] Übergabe testen und absichern

## 🗝️ Schlüsselbegriffe (für GitHub-Suche)

`n8n`, `Webhook`, `Google Sheets`, `Automation`, `HTML Form`, `Testdaten`, `GitHub Pages`, `Service Account`, `low-code`, `Datenweitergabe`, `form to sheet`, `Formularverarbeitung`, `workflow demo`, `self-hosted`, `no-code`, `Public Webhook`, `n8n credentials`, `Beispielprojekt`, `portfolio`

---

📎 Dieses Projekt dient als persönliches Lern- und Demonstrationsprojekt zur Automatisierung von Formularprozessen mit Open-Source-Tools.
