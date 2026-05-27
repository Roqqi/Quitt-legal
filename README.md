# Quitt – Rechtliche Dokumente

Anbieter: Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me

---

## Dateien in diesem Ordner

| Datei | Zweck | Status |
|---|---|---|
| `IMPRESSUM.md` | Anbieterkennzeichnung (§ 5 DDG) | ⚠️ Finanzamt + Steuernummer fehlt noch |
| `DATENSCHUTZ.md` | Datenschutzerklärung (DSGVO) | ✅ Fertig (inkl. Cloud-Sync / Supabase) |
| `AGB.md` | Allgemeine Geschäftsbedingungen | ✅ Fertig (inkl. Cloud-Sync / Supabase) |
| `NUTZUNGSBEDINGUNGEN.md` | App-Nutzungsregeln (Apple Pflicht) | ✅ Fertig |

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

### GitHub Pages (kostenloses Hosting für App Store URLs)

Apple und Google verlangen eine öffentlich erreichbare URL für die Datenschutzerklärung.

1. GitHub → Dieses Repo → **Settings** → **Pages**
2. Source: **Deploy from branch** → `main` → `/root` → **Save**
3. Nach ~2 Minuten läuft: `https://roqqi.github.io/Quitt-legal/DATENSCHUTZ`
4. Diese URL in App Store Connect und Google Play Console eintragen

### In der App selbst (SettingsScreen.tsx)

```typescript
import { Linking } from 'react-native';

const LEGAL_URLS = {
  datenschutz: 'https://roqqi.github.io/Quitt-legal/DATENSCHUTZ',
  agb: 'https://roqqi.github.io/Quitt-legal/AGB',
  nutzungsbedingungen: 'https://roqqi.github.io/Quitt-legal/NUTZUNGSBEDINGUNGEN',
  impressum: 'https://roqqi.github.io/Quitt-legal/IMPRESSUM',
};
```

---

## Apple App Store Checkliste (Pflichtfelder)

Beim Einreichen der App in App Store Connect brauchst du:

- [ ] **Privacy Policy URL** → GitHub Pages URL der DATENSCHUTZ.md
- [ ] **Support URL** → `mailto:RoqqiStudios@proton.me`
- [ ] **Marketing URL** → optional (Landing Page)

---

*Dennis Meilicke | RoqqiStudios | RoqqiStudios@proton.me*  
*Zuletzt aktualisiert: 27. Mai 2026*
