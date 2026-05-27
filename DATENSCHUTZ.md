# Datenschutzerklärung

*Stand: 27. Mai 2026*

## 1. Verantwortlicher

Verantwortlicher im Sinne der Datenschutz-Grundverordnung (DSGVO) ist:

**Dennis Meilicke**  
RoqqiStudios  
Waldstr. 21  
15518 Steinhöfel  
Deutschland

E-Mail: RoqqiStudios@proton.me

---

## 2. Grundsätze der Datenverarbeitung

Die App **Quitt** kann in zwei Modi genutzt werden:

**Ohne Konto (lokal):**  
Alle von Ihnen eingegebenen Daten werden ausschließlich lokal auf Ihrem Gerät gespeichert. Es findet keine Übertragung an externe Server statt. Wir haben zu keinem Zeitpunkt Zugriff auf Ihre Daten.

**Mit Konto (Cloud-Sync):**  
Wenn Sie sich mit Apple Sign-In oder Google Sign-In anmelden, werden Ihre Geschäftsdaten zur geräteübergreifenden Synchronisation verschlüsselt auf Servern von Supabase Inc. (Rechenzentrum: AWS eu-central-1, Frankfurt, Deutschland) gespeichert. Ihre Gewerbedaten (Firmenname, Steuernummer, Bankdaten, Logo) verbleiben dabei stets ausschließlich lokal auf Ihrem Gerät.

---

## 3. Welche Daten werden verarbeitet?

### 3.1 Lokale Daten (immer auf Ihrem Gerät)

Folgende Daten werden stets nur lokal in einer SQLite-Datenbank auf Ihrem Gerät gespeichert – unabhängig davon, ob Sie ein Konto nutzen:

- **Gewerbedaten:** Firmenname, Inhabername, Adresse, Steuernummer, USt-ID, Bankverbindung, Logo

Ohne Konto werden zusätzlich alle weiteren Daten (Kunden, Artikel, Rechnungen, Kassenbuch, Zeiterfassung) ausschließlich lokal gespeichert.

### 3.2 Cloud-Daten (nur mit Konto)

Wenn Sie ein Konto anlegen, werden folgende Daten zusätzlich auf Servern von **Supabase Inc.** (AWS eu-central-1, Frankfurt, Deutschland) gespeichert:

- **Kontodaten:** E-Mail-Adresse (aus Ihrem Apple- oder Google-Konto), anonymisierte Nutzer-ID
- **Kundendaten:** Name, Anschrift, E-Mail, Telefon, USt-ID Ihrer Kunden
- **Artikeldaten:** Artikelbezeichnungen, Preise
- **Projektdaten:** Projektbezeichnungen, Kundenzuordnung
- **Rechnungsdaten:** Rechnungsnummern, Positionen, Beträge, Zahlungsstatus
- **Kassenbuchdaten:** Einnahmen, Ausgaben, Kategorien
- **Zeiterfassungsdaten:** Zeiteinträge, Projektzuordnungen

### 3.3 Authentifizierungsdaten (bei Kontoanmeldung)

Bei der Anmeldung mit **Apple Sign-In** oder **Google Sign-In** erhalten wir ausschließlich:
- Ihre E-Mail-Adresse
- Eine anonymisierte Nutzer-ID des jeweiligen Anbieters

Passwörter werden von uns nicht verarbeitet. Die Authentifizierung erfolgt direkt über Apple bzw. Google auf Ihrem Gerät.

### 3.4 Technische Daten (App Store / Betriebssystem)

Beim Download und Betrieb der App über den **Apple App Store** oder **Google Play Store** können die jeweiligen Plattformbetreiber Daten erheben. Diese Verarbeitung unterliegt den Datenschutzbestimmungen von Apple bzw. Google:

- Apple Privacy Policy: [https://www.apple.com/de/privacy/](https://www.apple.com/de/privacy/)
- Google Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 3.5 In-App-Käufe (Pro-Version)

Käufe der Pro-Version werden über den jeweiligen App Store abgewickelt. Zahlungsdaten werden ausschließlich von Apple/Google verarbeitet — wir erhalten keine Zahlungsdaten.

### 3.6 Crash-Berichte und Diagnose

Die App übermittelt keine Crash-Berichte oder Nutzungsstatistiken an externe Dienste.

---

## 4. Auftragsverarbeiter (Art. 28 DSGVO)

Wir setzen folgende Auftragsverarbeiter ein:

| Anbieter | Zweck | Sitz / Datenstandort | Datenschutz |
|---|---|---|---|
| **Supabase, Inc.** | Cloud-Sync, Authentifizierung | Singapur / AWS eu-central-1, Frankfurt, DE | [supabase.com/privacy](https://supabase.com/privacy) |
| **Apple Distribution International Ltd.** | Apple Sign-In | Cork, Irland | [apple.com/de/privacy](https://www.apple.com/de/privacy/) |
| **Google Ireland Limited** | Google Sign-In | Dublin, Irland | [policies.google.com/privacy](https://policies.google.com/privacy) |

Mit Supabase besteht ein Auftragsverarbeitungsvertrag (Data Processing Agreement). Soweit eine Übertragung in Drittländer stattfindet, erfolgt diese auf Basis von Standardvertragsklauseln gemäß Art. 46 Abs. 2 lit. c DSGVO.

---

## 5. Rechtsgrundlagen der Verarbeitung

- **Art. 6 Abs. 1 lit. b DSGVO:** Vertragserfüllung (Bereitstellung der App-Funktionen)
- **Art. 6 Abs. 1 lit. a DSGVO:** Einwilligung (Anlage eines Kontos und Cloud-Sync; widerrufbar durch Abmelden oder Kontolöschung)
- **Art. 6 Abs. 1 lit. f DSGVO:** Berechtigte Interessen (App-Stabilität)

---

## 6. Speicherdauer und Löschung

**Lokale Daten** werden auf Ihrem Gerät gespeichert bis zur Deinstallation der App oder manuellen Löschung.

**Cloud-Daten (mit Konto):**
- Verbleiben auf den Supabase-Servern, solange Ihr Konto aktiv ist
- Werden vollständig und unwiderruflich gelöscht, wenn Sie Ihr Konto löschen
- Kontolöschung: Anfrage per E-Mail an RoqqiStudios@proton.me

---

## 7. Ihre Rechte nach DSGVO

Sie haben folgende Rechte bezüglich Ihrer personenbezogenen Daten:

| Recht | Grundlage | Umsetzung in Quitt |
|---|---|---|
| **Auskunft** (Art. 15) | Welche Daten werden verarbeitet? | Alle Daten in der App einsehbar; Cloud-Daten auf Anfrage |
| **Berichtigung** (Art. 16) | Falsche Daten korrigieren | Direkt in der App bearbeitbar |
| **Löschung** (Art. 17) | „Recht auf Vergessenwerden" | In der App löschbar; Kontolöschung inkl. Server-Daten auf Anfrage |
| **Einschränkung** (Art. 18) | Verarbeitung einschränken | Wechsel zu lokalem Modus (Konto abmelden) |
| **Datenübertragbarkeit** (Art. 20) | Export der Daten | CSV-Export (Pro-Funktion) |
| **Widerruf der Einwilligung** | Cloud-Sync abschalten | App ohne Konto nutzen oder Konto löschen |
| **Widerspruch** (Art. 21) | Gegen Verarbeitung widersprechen | Kontakt per E-Mail |

Zur Ausübung Ihrer Rechte wenden Sie sich an: RoqqiStudios@proton.me

---

## 8. Datensicherheit

**Lokale Daten** sind durch die Sicherheitsmechanismen Ihres Betriebssystems geschützt (iOS App-Sandbox, Geräteverschlüsselung, Face ID / Touch ID).

**Cloud-Daten** werden verschlüsselt übertragen (TLS 1.2+) und bei Supabase auf verschlüsselten AWS-Servern (AES-256) gespeichert. Der Zugriff auf Ihre Daten ist durch Row-Level Security (RLS) auf Ihren Account beschränkt — kein anderer Nutzer kann Ihre Daten einsehen.

---

## 9. Hinweis zur eigenen DSGVO-Pflicht der Quitt-Nutzer

Wenn Sie Kundendaten in Quitt eingeben und die Cloud-Sync-Funktion nutzen, übermitteln Sie personenbezogene Daten Ihrer Kunden an Supabase. Als Verantwortlicher (Art. 4 Nr. 7 DSGVO) sind Sie verpflichtet, Ihre Kunden gemäß Art. 13, 14 DSGVO über diese Verarbeitung zu informieren. Wir empfehlen, dies in Ihrer eigenen Datenschutzerklärung zu berücksichtigen.

---

## 10. Kinder

Quitt ist eine App für gewerbliche Nutzer und nicht für Personen unter 18 Jahren bestimmt. Wir erheben wissentlich keine personenbezogenen Daten von Kindern.

---

## 11. Änderungen dieser Datenschutzerklärung

Wir behalten uns vor, diese Datenschutzerklärung anzupassen, um sie an geänderte Rechtslage oder Änderungen am Dienst anzupassen. Die jeweils aktuelle Version ist im GitHub-Repository abrufbar. Nutzer mit Konto werden bei wesentlichen Änderungen per App-Hinweis informiert.

---

## 12. Beschwerderecht

Sie haben das Recht, sich bei einer Datenschutzaufsichtsbehörde zu beschweren. Die zuständige Behörde für Brandenburg ist:

**Die Landesbeauftragte für den Datenschutz und für das Recht auf Akteneinsicht Brandenburg**  
Stahnsdorfer Damm 77  
14532 Kleinmachnow  
Web: [https://www.lda.brandenburg.de](https://www.lda.brandenburg.de)

---

*Stand: 27. Mai 2026*  
*Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me*
