# Datenschutzerklärung

**Dragon Hoard - Spielesammlungs-Tracker**

Zuletzt aktualisiert: 20. Februar 2026

---

## 1. Einleitung

Dragon Hoard ("wir", "uns" oder "unser") betreibt die mobile Anwendung Dragon Hoard (die "App"). Diese Datenschutzerklärung erläutert, wie wir Ihre persönlichen Daten erfassen, verwenden und schützen, wenn Sie unsere App nutzen.

Durch die Nutzung von Dragon Hoard stimmen Sie der Erfassung und Verwendung von Informationen gemäß dieser Richtlinie zu.

---

## 2. Welche Daten wir erfassen

### 2.1 Kontoinformationen
- **E-Mail-Adresse**: Erforderlich für Kontoerstellung und Anmeldung (bei E-Mail-Anmeldung)
- **Apple-ID**: Bei Anmeldung mit Apple erhalten wir Ihren Namen und Ihre E-Mail (oder eine Relay-Adresse, wenn Sie diese verbergen)
- **Gastkonten**: Sie können die App ohne Angabe persönlicher Daten nutzen. Gastkonten sind anonym und nur mit Ihrem Gerät verknüpft.

### 2.2 Spielesammlungsdaten
- Spieletitel, Plattformen und Status (Backlog, Spielend, Abgeschlossen)
- Kaufpreise und geschätzte Marktwerte
- Spielzustand, Region und Anzahl
- Persönliche Notizen und Bewertungen
- Wunschlisten-Einträge

### 2.3 Kamera und Fotos
- Bei Nutzung des Regal-Scanners greift die App auf Ihre Kamera zu, um Spieleregale zu fotografieren
- Fotos werden zur Spielerkennung an Google Gemini AI gesendet und **nicht** auf unseren Servern gespeichert
- Fotos werden nur im Arbeitsspeicher verarbeitet und nach der Erkennung sofort verworfen

### 2.4 Nutzungsdaten
- Statistiken zur App-Funktionsnutzung (nur mit Ihrer Zustimmung)
- Spar-Tracking-Daten
- Fortschritt bei Erfolgen und Abzeichen
- Tägliche Streak- und XP-Daten

### 2.5 Technische Informationen
- Gerätetyp und Betriebssystem (für App-Kompatibilität)
- App-Version
- Geräte-Locale und Region (für Währungs- und Spracheinstellungen)

**Hinweis:** Mit Ihrer ausdrücklichen Zustimmung können wir anonymisierte Absturzberichte und Nutzungsstatistiken erfassen, um die App zu verbessern (siehe Abschnitt 4.5). Sie können dies jederzeit in den App-Einstellungen aktivieren oder deaktivieren.

---

## 3. Wie wir Ihre Daten verwenden

Wir verwenden Ihre Daten, um:
- Die Funktionalität der App bereitzustellen und zu pflegen
- Ihre Spielesammlung geräteübergreifend zu synchronisieren
- Den geschätzten Marktwert Ihrer Sammlung basierend auf öffentlichen Verkaufsdaten zu berechnen
- Ihre Ersparnisse und Gaming-Ziele zu verfolgen
- Wichtige Service-Benachrichtigungen zu senden
- Die App basierend auf Nutzungsmustern zu verbessern (mit Zustimmung)

Wir verkaufen Ihre persönlichen Daten **nicht** an Dritte.

---

## 4. Drittanbieter-Dienste

Dragon Hoard nutzt folgende Drittanbieter-Dienste:

### 4.1 Supabase (Datenbank & Authentifizierung)
- Speichert Ihre Konto- und Sammlungsdaten auf sicheren Servern
- Verwaltet die Authentifizierung (E-Mail/Passwort und anonyme Anmeldung)
- Daten sind durch Row Level Security geschützt — nur Sie können auf Ihre Daten zugreifen
- Datenschutzerklärung: https://supabase.com/privacy

### 4.2 RevenueCat (Abonnement-Verwaltung)
- Verwaltet Premium-Abonnements und In-App-Käufe
- Erhält Ihre anonyme Benutzer-ID und den Abonnementstatus
- Erhält nicht Ihre E-Mail, Ihren Namen oder Ihre Spielesammlungsdaten
- Datenschutzerklärung: https://www.revenuecat.com/privacy

### 4.3 Google Gemini AI (Regal-Scanner)
- Verarbeitet Fotos zur Erkennung von Spielen in Ihrem Regal
- Bilder werden über unseren sicheren Server (Supabase Edge Function) gesendet, nicht direkt von Ihrem Gerät
- Bilder werden in Echtzeit verarbeitet und weder von uns noch von Google über die Anfrage hinaus **gespeichert**
- Datenschutzerklärung: https://policies.google.com/privacy

### 4.4 IGDB (Spiele-Datenbank)
- Liefert Spieleinformationen, Cover-Bilder und Metadaten
- Es werden nur Spielsuchanfragen gesendet — keine persönlichen Daten
- Datenschutzerklärung: https://www.igdb.com/privacy_policy

### 4.5 Firebase Analytics & Crashlytics (Google)
- Erfasst anonymisierte Nutzungsstatistiken und Absturzberichte (**nur mit Ihrer Zustimmung**)
- Es werden keine persönlichen Daten geteilt — nur aggregierte Metriken
- Sie können dies jederzeit in den App-Einstellungen deaktivieren
- Datenschutzerklärung: https://firebase.google.com/support/privacy

### 4.6 Jina.ai & eBay (Preisschätzung)
- Wird verwendet, um Spielmarktwerte anhand öffentlich zugänglicher eBay-Verkaufsdaten zu schätzen
- Jina.ai liest in unserem Auftrag öffentliche eBay-Suchergebnisseiten
- Es werden nur Spieletitel und Plattformnamen gesendet — **keine persönlichen Daten**
- Preisschätzungen sind Näherungswerte basierend auf kürzlichen abgeschlossenen Verkäufen
- Datenschutzerklärung (Jina): https://jina.ai/legal/privacy-policy

---

## 5. Datenspeicherung und Sicherheit

- Ihre Daten werden auf sicheren Servern von Supabase gespeichert
- Alle Datenübertragungen sind mit HTTPS/TLS verschlüsselt
- Passwörter werden gehasht und niemals im Klartext gespeichert
- Sensible lokale Daten (Abonnementstatus, Fortschritt) werden im verschlüsselten Keychain Ihres Geräts gespeichert
- Nicht-sensible Einstellungen werden lokal auf Ihrem Gerät gespeichert
- Wir implementieren branchenübliche Sicherheitsmaßnahmen

---

## 6. Ihre Rechte

Sie haben das Recht auf:
- **Auskunft**: Eine Kopie Ihrer persönlichen Daten anzufordern
- **Berichtigung**: Ihre Informationen zu aktualisieren oder zu korrigieren
- **Löschung**: Ihr Konto und alle zugehörigen Daten zu löschen (verfügbar in den App-Einstellungen)
- **Export**: Ihre Spielesammlungsdaten zu exportieren (PDF-Export-Funktion)

Die Kontolöschung entfernt dauerhaft alle Ihre Daten von unseren Servern und löscht alle lokal gespeicherten Daten von Ihrem Gerät.

Um diese Rechte auszuüben, nutzen Sie die In-App-Einstellungen oder kontaktieren Sie uns per E-Mail.

---

## 7. Datenspeicherung

- Aktive Konten: Daten werden aufbewahrt, solange das Konto aktiv ist
- Gelöschte Konten: Alle Daten werden bei Anfrage sofort dauerhaft gelöscht
- Anonyme Absturzberichte: Werden bis zu 90 Tage aufbewahrt

---

## 8. Internationale Datenübermittlung

Ihre Daten können in Ländern außerhalb Ihres Wohnsitzlandes verarbeitet werden. Supabase-Server können sich in der EU oder den USA befinden. Alle Übertragungen sind durch HTTPS-Verschlüsselung geschützt und entsprechen den geltenden Datenschutzbestimmungen.

---

## 9. Datenschutz für Kinder

Dragon Hoard ist nicht für Kinder unter 13 Jahren bestimmt. Wir erfassen wissentlich keine persönlichen Daten von Kindern unter 13 Jahren.

---

## 10. Änderungen dieser Richtlinie

Wir können diese Datenschutzerklärung von Zeit zu Zeit aktualisieren. Über wesentliche Änderungen informieren wir Sie über die App oder per E-Mail.

---

## 11. Kontakt

Bei Fragen zu dieser Datenschutzerklärung oder Ihren persönlichen Daten:

**E-Mail**: hoardgamecollection@gmail.com

---

*Diese Datenschutzerklärung gilt ab dem 20. Februar 2026.*
