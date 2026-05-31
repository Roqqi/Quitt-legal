# Quitt – Rechtliche Dokumente

Anbieter: Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me

---

## Dateien in diesem Ordner

| Datei | Zweck | Status |
|---|---|---|
| `IMPRESSUM.md` | Anbieterkennzeichnung (§ 5 TMG) | ⚠️ Finanzamt + Steuernummer fehlt noch |
| `DATENSCHUTZ.md` | Datenschutzerklärung (DSGVO) | ✅ Fertig |
| `AGB.md` | Allgemeine Geschäftsbedingungen | ✅ Fertig |
| `NUTZUNGSBEDINGUNGEN.md` | App-Nutzungsregeln (Apple Pflicht) | ✅ Fertig |
| `APP_STORE_TEXTE.md` | Fertige Texte für App Store / Play Store | ✅ Fertig |

---

## Was noch fehlt (einmalig nachtragen)

Öffne `IMPRESSUM.md` und ersetze:

```
[DEIN FINANZAMT]   → z.B. "Finanzamt Frankfurt (Oder)"
[STEUERNUMMER]     → deine persönliche Steuernummer
```

Das war's. Alle anderen Platzhalter sind bereits ausgefüllt.

---

## Wo kommen die Dokumente hin?

### GitHub Repository (Struktur)
```
quitt/
├── legal/
│   ├── README.md
│   ├── IMPRESSUM.md
│   ├── DATENSCHUTZ.md
│   ├── AGB.md
│   ├── NUTZUNGSBEDINGUNGEN.md
│   └── APP_STORE_TEXTE.md
└── src/
    └── ...
```

### GitHub Pages (kostenloses Hosting für App Store URLs)

Apple und Google verlangen eine öffentlich erreichbare URL für die Datenschutzerklärung.

1. GitHub → Dein Repo → **Settings** → **Pages**
2. Source: **Deploy from branch** → `main` → `/root` → **Save**
3. Nach ~2 Minuten läuft: `https://[dein-github-user].github.io/quitt/legal/DATENSCHUTZ`
4. Diese URL in App Store Connect und Google Play Console eintragen

### In der App selbst (SettingsScreen.tsx)

```typescript
import { Linking } from 'react-native';

const LEGAL_URLS = {
  impressum: 'https://[dein-github-user].github.io/quitt/legal/IMPRESSUM',
  datenschutz: 'https://[dein-github-user].github.io/quitt/legal/DATENSCHUTZ',
  agb: 'https://[dein-github-user].github.io/quitt/legal/AGB',
  nutzungsbedingungen: 'https://[dein-github-user].github.io/quitt/legal/NUTZUNGSBEDINGUNGEN',
};

// Beispiel Button
<TouchableOpacity onPress={() => Linking.openURL(LEGAL_URLS.datenschutz)}>
  <Text>Datenschutzerklärung</Text>
</TouchableOpacity>
```

---

## Apple App Store Checkliste (Pflichtfelder)

Beim Einreichen der App in App Store Connect brauchst du:

- [ ] **Privacy Policy URL** → GitHub Pages URL deiner DATENSCHUTZ.md
- [ ] **Support URL** → z.B. `mailto:RoqqiStudios@proton.me`
- [ ] **Marketing URL** → optional (Landing Page)
- [ ] **App-Beschreibung** → aus `APP_STORE_TEXTE.md` kopieren
- [ ] **Keywords** → aus `APP_STORE_TEXTE.md` kopieren

---

*Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me*  
*Zuletzt aktualisiert: 17. Mai 2026*
