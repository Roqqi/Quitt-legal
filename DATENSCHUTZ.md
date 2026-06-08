# Datenschutzerklärung

*Stand: 31. Mai 2026*

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

Die App **Quitt** kann wahlweise ohne Konto (lokal) oder mit einem optionalen Konto (mit Cloud-Sync) genutzt werden:

**Ohne Konto (Gastmodus):**  
Alle eingegebenen Daten werden ausschließlich lokal auf Ihrem Gerät gespeichert. Es findet keine Übertragung an externe Server statt.

**Mit Konto (optionaler Cloud-Sync):**  
Bei Erstellung eines Benutzerkontos werden Ihre Geschäftsdaten optional mit unserer Cloud-Infrastruktur (Supabase, gehostet in der EU) synchronisiert, um den Zugriff von mehreren Geräten zu ermöglichen. Dabei wird eine E-Mail-Adresse zur Authentifizierung verarbeitet.

Es werden **keine Daten für Werbezwecke** verarbeitet und keine Daten an Dritte zu kommerziellen Zwecken weitergegeben.

---

## 3. Welche Daten werden verarbeitet?

### 3.1 Daten ohne Konto (lokal)

Folgende Daten werden **ausschließlich lokal auf Ihrem Gerät** gespeichert (SQLite-Datenbank):

- **Gewerbedaten:** Firmenname, Inhabername, Adresse, Steuernummer, USt-ID, Bankverbindung, Logo
- **Kundendaten:** Name, Anschrift, E-Mail, Telefon, USt-ID Ihrer Kunden
- **Artikeldaten:** Artikelbezeichnungen, Preise, Produktfotos
- **Rechnungsdaten:** Rechnungsnummern, Positionen, Beträge, Zahlungsstatus
- **Kassenbuchdaten:** Einnahmen, Ausgaben, Kategorien, Belegfotos

Diese Daten verlassen Ihr Gerät nicht, außer wenn Sie selbst eine Rechnung als PDF teilen.

### 3.2 Daten mit Konto (Cloud-Sync)

Bei Nutzung eines Kontos werden zusätzlich folgende Daten verarbeitet:

- **E-Mail-Adresse** (zur Authentifizierung via Apple Sign-In)
- **Benutzer-ID** (von unserem Authentifizierungsdienstleister vergeben)
- **Ihre Geschäftsdaten** (Kunden, Artikel, Rechnungen, Kassenbuch — synchronisiert auf unsere Server)

Die Daten werden verschlüsselt übertragen (TLS) und auf Servern in der EU gespeichert.

### 3.3 Technische Daten (App Store)

Beim Download und Betrieb der App über den **Apple App Store** können plattformseitige Daten erhoben werden. Diese Verarbeitung unterliegt der Datenschutzbestimmung von Apple:

- Apple Privacy Policy: [https://www.apple.com/de/privacy/](https://www.apple.com/de/privacy/)

### 3.4 In-App-Käufe (Pro-Version)

Käufe der Pro-Version werden über Apple In-App Purchase abgewickelt. Zahlungsdaten werden ausschließlich von Apple verarbeitet — wir erhalten keine Zahlungsdaten.

### 3.5 Crash-Berichte und Diagnose

Die App übermittelt **keine** Crash-Berichte oder Nutzungsstatistiken an externe Dienste.

---

## 4. Auftragsverarbeiter

Für die optionale Konto-Funktion setzen wir folgenden Auftragsverarbeiter ein:

**Supabase, Inc.**  
970 Toa Payoh North, Singapur (Serverstandorte EU)  
Datenschutz: [https://supabase.com/privacy](https://supabase.com/privacy)

Mit Supabase besteht ein Auftragsverarbeitungsvertrag gemäß Art. 28 DSGVO. Die Daten werden ausschließlich zur Bereitstellung des Cloud-Sync-Dienstes verarbeitet.

---

## 5. Rechtsgrundlagen der Verarbeitung

- **Art. 6 Abs. 1 lit. b DSGVO:** Verarbeitung zur Vertragserfüllung (Bereitstellung der App-Funktionen)
- **Art. 6 Abs. 1 lit. a DSGVO:** Einwilligung (bei Erstellung eines optionalen Kontos)

---

## 6. Speicherdauer und Löschung

**Lokale Daten:** Verbleiben auf Ihrem Gerät bis zur Deinstallation oder manuellen Löschung.

**Cloud-Daten (bei Konto):** Werden auf unseren Servern gespeichert, bis Sie Ihr Konto löschen. Die Kontolöschung ist direkt in der App möglich (Einstellungen → Konto & Sync → Account löschen). Dabei werden alle mit Ihrem Konto verknüpften Daten dauerhaft gelöscht.

---

## 7. Ihre Rechte nach DSGVO

Sie haben folgende Rechte bezüglich Ihrer personenbezogenen Daten:

| Recht | Grundlage | Umsetzung in Quitt |
|---|---|---|
| **Auskunft** (Art. 15) | Welche Daten werden verarbeitet? | Alle Daten in der App einsehbar |
| **Berichtigung** (Art. 16) | Falsche Daten korrigieren | Direkt in der App bearbeitbar |
| **Löschung** (Art. 17) | „Recht auf Vergessenwerden" | In der App: Einstellungen → Account löschen |
| **Einschränkung** (Art. 18) | Verarbeitung einschränken | Kontakt per E-Mail |
| **Datenübertragbarkeit** (Art. 20) | Export der Daten | CSV-Export (Pro-Funktion) |
| **Widerspruch** (Art. 21) | Gegen Verarbeitung widersprechen | Kontakt per E-Mail |

Zur Ausübung Ihrer Rechte wenden Sie sich an: RoqqiStudios@proton.me

---

## 8. Datensicherheit

**Lokale Daten** sind durch die Sicherheitsmechanismen von iOS geschützt (App-Sandbox, Geräteverschlüsselung, Face ID / Touch ID).

**Cloud-Daten** werden verschlüsselt übertragen (TLS 1.2+) und sicher gespeichert. Der Zugriff ist auf Ihren Account beschränkt (Row Level Security).

Wir empfehlen, Ihr Gerät mit einem sicheren Passcode zu sichern und bei Nutzung ohne Konto regelmäßige iCloud-Backups durchzuführen.

---

## 9. GoBD-Hinweis

Quitt unterstützt wesentliche Grundsätze der GoBD (Grundsätze zur ordnungsmäßigen Führung und Aufbewahrung von Büchern, Aufzeichnungen und Unterlagen in elektronischer Form):

- Fortlaufende, lückenlose Rechnungsnummern
- Keine Löschung von Rechnungen (nur Stornierung)
- Korrekte MwSt-Berechnung

Quitt ist jedoch **kein vollständig GoBD-zertifiziertes Buchführungssystem**. Insbesondere kann die gesetzlich vorgeschriebene 10-jährige Aufbewahrungspflicht nicht durch die App allein gewährleistet werden. Nutzer sind selbst verantwortlich, geeignete Archivierungsmaßnahmen (z.B. regelmäßige Exporte) zu treffen. Wir empfehlen ausdrücklich, einen Steuerberater hinzuzuziehen.

---

## 10. Kinder

Quitt ist eine App für gewerbliche Nutzer und nicht für Personen unter 18 Jahren bestimmt. Wir erheben wissentlich keine personenbezogenen Daten von Kindern.

---

## 11. Änderungen dieser Datenschutzerklärung

Wir behalten uns vor, diese Datenschutzerklärung bei geänderter Rechtslage oder Änderungen am Dienst anzupassen. Die jeweils aktuelle Version ist unter dieser URL abrufbar. Bei wesentlichen Änderungen werden Nutzer der Pro-Version informiert.

---

## 12. Beschwerderecht

Sie haben das Recht, sich bei einer Datenschutzaufsichtsbehörde zu beschweren. Die zuständige Behörde für Brandenburg ist:

**Die Landesbeauftragte für den Datenschutz und für das Recht auf Akteneinsicht Brandenburg**  
Stahnsdorfer Damm 77  
14532 Kleinmachnow  
Web: [https://www.lda.brandenburg.de](https://www.lda.brandenburg.de)

---

*Stand: 31. Mai 2026*  
*Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me*
