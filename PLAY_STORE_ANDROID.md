# Google Play Release – Quitt (Android)

*Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me*
*Paketname: `com.roqqistudios.quitt` · Stand: v1.2.0*

> Separate Vorlage nur für das **Google Play Console** Listing & die Pflichtformulare.
> Alle Texte auf dem korrigierten Modell-Stand (Free 3/5/10, Lifetime 44,99 €, optionale Cloud-Sync).

---

## 1. Store-Eintrag (Copy-Paste)

### App-Titel (max. 30 Zeichen)
```
Quitt – Rechnung & Kassenbuch
```

### Kurzbeschreibung (max. 80 Zeichen)
```
Profi-Rechnungen in Sekunden. Kassenbuch für Kleinunternehmer.
```

### Vollständige Beschreibung (max. 4.000 Zeichen)
```
Quitt ist die Rechnungs-App für Einzelunternehmer, die endlich keine Lust mehr auf Word-Vorlagen haben.

RECHNUNGEN IN SEKUNDEN
Kunden und Artikel einmal anlegen – dann nur noch auswählen, Menge eingeben und auf „PDF erstellen" tippen. Fertig. Die Rechnung landet per WhatsApp, Mail oder als Download direkt beim Kunden.

✓ GoBD-konforme Rechnungsnummerierung
✓ Alle MwSt-Sätze (0%, 7%, 19%)
✓ Variable Versandkosten und Rabatte
✓ Artikelstamm mit Foto, Nummer und Preis
✓ Kundenstamm mit allen Rechnungsdaten
✓ Gewerbedaten und Logo auf jeder Rechnung

KASSENBUCH OHNE CHAOS
Dokumentiere Einnahmen und Ausgaben direkt in der App. Foto vom Beleg machen, Betrag eingeben – fertig. Der Monatsüberblick zeigt sofort, wie der Laden läuft.

DEINE DATEN – DEIN GERÄT
Quitt speichert standardmäßig alles lokal – kein Konto nötig, kein Abo für die Basis-Funktionen. Auf Wunsch synchronisierst du deine Daten verschlüsselt über die Cloud (EU-Server) auf all deinen Geräten. Du entscheidest.

FÜR WEN?
Handwerker · Fotografen · Flohmarkthändler · Reinigungskräfte · Coaches · Freelancer · Alle mit Kleingewerbe

PRO-VERSION: Ab € 4,99/Monat (oder einmalig € 44,99)
→ Unbegrenzte Rechnungen, Artikel und Kunden
→ Unbegrenzte Daueraufträge
→ EÜR-Export als PDF
→ Angebote erstellen
→ Mahnwesen
→ CSV-Export für den Steuerberater

Quitt. Rechnung raus. Erledigt. Weiter.
```

### Kategorie & Kontakt
- **App-Kategorie:** Unternehmen (Business)
- **Tags:** Finanzen, Buchhaltung
- **Kontakt-E-Mail:** `RoqqiStudios@proton.me`
- **Datenschutz-URL:** `https://<github-pages-oder-domain>/DATENSCHUTZ`  *(Pflicht – muss öffentlich erreichbar sein)*

---

## 2. Release Notes – „Was ist neu" (max. 500 Zeichen)

```
Willkommen bei Quitt für Android!

• Rechnungen in Sekunden erstellen & als PDF teilen
• GoBD-konforme Rechnungsnummern
• Kassenbuch mit Belegfotos & Monatsüberblick
• Kunden- und Artikelstamm
• Daueraufträge, Angebote, Mahnwesen & EÜR-Export (Pro)
• Optionale, verschlüsselte Cloud-Sync (EU)

Feedback? RoqqiStudios@proton.me
```

---

## 3. Data-Safety-Formular (Datensicherheit)

**Grundsatz:** Ohne Konto verlässt **kein** Datum das Gerät. Erst wenn der Nutzer
sich anmeldet (optionale Cloud-Sync via Supabase, EU-Server), werden Daten übertragen.
→ Bei jeder Datenart: **Erhebung = optional**.

### Allgemeine Angaben
| Frage | Antwort |
|---|---|
| Werden Daten erhoben/geteilt? | **Ja, erhoben** (nur bei aktivem Konto) |
| Werden Daten an Dritte **weitergegeben** (shared)? | **Nein** – Supabase ist Auftragsverarbeiter, keine Weitergabe zu Werbe-/Drittzwecken |
| Übertragung **verschlüsselt** (in transit)? | **Ja** (HTTPS/TLS) |
| Nutzer kann **Löschung** beantragen? | **Ja** (siehe Abschnitt 4 – Konto-Löschung) |
| Erhebung erforderlich oder optional? | **Optional** (nur mit Konto/Sync) |

### Erhobene Datenarten
| Google-Kategorie | Konkret in Quitt | Zweck |
|---|---|---|
| **Personenbez. Infos – Name** | Inhaber-/Firmenname, Kontaktname (Kunden) | App-Funktion (Sync) |
| **Personenbez. Infos – E-Mail** | Login-E-Mail (Apple/Google), Profil-/Kunden-E-Mail | App-Funktion, Konto-Verwaltung |
| **Personenbez. Infos – Adresse** | Gewerbe- & Kundenadressen | App-Funktion (Sync) |
| **Personenbez. Infos – Telefonnr.** | Profil- & Kundentelefon | App-Funktion (Sync) |
| **Personenbez. Infos – Sonstige** | Steuernr., USt-IdNr. | App-Funktion (Sync) |
| **Finanzinfos – Sonstige Finanzinfos** | IBAN/BIC/Bank, Rechnungs- & Kassenbuchbeträge | App-Funktion (Sync) |
| **Fotos & Videos** | Logo, Artikelbilder, Belegfotos | App-Funktion (Sync) |
| **App-Aktivität** | Projekte, Zeiterfassung | App-Funktion (Sync) |

> Für **alle** Zeilen: Zweck = „App-Funktionalität"; **kein** Tracking, **keine** Werbung,
> **keine** Weitergabe. Erhebung jeweils **optional**.

**Nicht erhoben:** Standort, Kontakte (Geräteadressbuch), Browserverlauf, Health/Fitness,
Kalender, SMS, Geräte-IDs für Werbung.

### Käufe (In-App)
IAP-Zahlungen werden **vollständig von Google Play** abgewickelt – Quitt erhält/speichert
**keine** Zahlungsdaten. Im Data-Safety-Formular daher **nicht** als „erhobene Zahlungsinfo" angeben.

---

## 4. ⚠️ Pflicht: Konto-Löschung (Account Deletion)

Quitt erlaubt Konto-Erstellung (Apple/Google-Login) → Google verlangt zwingend:
1. **In-App-Weg** zum Löschen des Kontos **und** der zugehörigen Cloud-Daten.
2. Eine **öffentliche Web-URL** zur Löschanfrage (im Play Console unter „Datensicherheit → Konto-Löschung" zu hinterlegen).

> **To-do vor Einreichung prüfen:** Gibt es in den Einstellungen bereits „Konto löschen"?
> Falls nicht, muss das vor dem Review ergänzt werden – sonst Ablehnung.

---

## 4a. App-Review-Hinweis: Account-Löschung finden

Die Konto-Löschung ist **nur nach Login sichtbar** (lokale Nutzer haben kein Konto).
Damit der Prüfer sie findet, diesen Hinweis in die Review-Notizen eintragen
(Play Console: „App-Inhalte → App-Zugriff" / App Store Connect: „App Review Information → Notes"):

**Deutsch**
```
Konto-Löschung: Mit Apple oder Google anmelden → Tab „Profil/Einstellungen“ → Abschnitt „KONTO & SYNC“ → „Account löschen“. Löscht den Account und alle zugehörigen Cloud-Daten unwiderruflich. Ohne Konto nutzt die App nur lokalen Speicher (kein Account, daher keine Löschoption nötig).
```

**English**
```
Account deletion: Sign in with Apple or Google → "Profile/Settings" tab → "KONTO & SYNC" section → "Account löschen" (Delete account). This permanently deletes the account and all associated cloud data. Without an account the app stores data locally only (no account, so no deletion option is needed).
```

> Falls für IAP-Tests ein Demo-Zugang verlangt wird: ein Apple/Google-Testkonto
> bereithalten oder den lokalen Modus („Ohne Konto fortfahren") als Review-Weg angeben.

---

## 5. Pflicht-Checkliste vor Einreichung
- [ ] AAB gebaut: `eas build --platform android --profile production`
- [ ] In-App-Produkte angelegt (`.monthly`, `.annual`, `.lifetime` – siehe Code `PremiumContext.tsx`)
- [ ] Datenschutz-URL öffentlich erreichbar
- [ ] Data-Safety-Formular ausgefüllt (Abschnitt 3)
- [ ] Konto-Löschung in-App + URL (Abschnitt 4)
- [ ] Inhaltseinstufung (Fragebogen) + Zielgruppe ausgefüllt
- [ ] Grafiken: Feature-Grafik 1024×500, Icon 512×512, ≥ 2 Screenshots
- [ ] App in Internal-Testing-Track hochgeladen + Lizenz-Tester für IAP eingetragen
