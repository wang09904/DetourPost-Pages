## 1. Einführung

Detour Post (im Folgenden als „die App“ bezeichnet) wird von Yong Wang (im Folgenden als „wir“, „uns“ oder „unser“ bezeichnet) betrieben. Wir fungieren als Datenverantwortlicher für Ihre personenbezogenen Daten.

In dieser Datenschutzrichtlinie wird erklärt, welche Informationen wir sammeln, warum wir sie verarbeiten, wie sie gehandhabt und gespeichert werden, welche Aufbewahrungsfristen es gibt und wie Sie Ihre Datenschutzrechte ausüben können.

Unser Grundprinzip ist einfach: **Ihre Briefe sind zwischen Ihnen und Ihrem Empfänger privat. Wir können sie nicht lesen und haben auch nicht die Absicht, sie zu lesen.**

## 2. Informationen, die wir verarbeiten

### 2.1 Informationen, die Sie aktiv bereitstellen

| Informationen | Einzelheiten | Notwendigkeit |
|---|---|---|
| Konto-ID | Eindeutige Kennung, die Sie über „Mit Apple anmelden“ oder „Google |“ erhalten Erforderlich für die Kontoerstellung |
| Anmeldedaten | Sitzungsauthentifizierungstoken | Erforderlich für sicheren Zugriff |
| Geburtsdatum und Region | Wird bei der Registrierung ausschließlich zur Feststellung der Altersberechtigung verwendet | Erforderlich für die Registrierung. **Das Geburtsdatum wird nur zum Zeitpunkt der Auswertung verwendet und sofort verworfen. Wir speichern es nie.** Nur die Regelversion und die ausgewählte Region bleiben erhalten |
| Anzeigename | Benutzerdefinierter Name in Ihrem Profil festgelegt, sichtbar für Ihre Empfänger | Optional |
| Stadt | Stadt als Abfahrts-/Ankunftsort ausgewählt | Optional, aber zum Versenden von Briefen erforderlich |
| Verbindungsinformationen | Beziehungsstatus, Einladungscodes und Anspruchsgeheimnisse | Zum Austausch von Briefen erforderlich |
| Briefinhalt | Brieftext, Briefpapierauswahl, beigefügte Fotos, Kurier, Ankunftszeit | Wird nur erstellt, wenn Sie sich für das Senden entscheiden |
| Berichtsdetails | Ausgewählte Verstoßkategorie (Belästigung, Spam, Sicherheit) und Ziel-ID. **Enthält KEINEN Buchstabentext, Fotos, Freiformtext oder Koordinaten**; blockiert automatisch die Party gleichzeitig | Wird nur erstellt, wenn Sie einen Bericht einreichen |
| Private Notizen | Private Notizen, die Sie einem Kontakt zuweisen | Optional. **Wird ausschließlich auf Ihrem lokalen Gerät gespeichert und niemals hochgeladen** |

**End-to-End-Verschlüsselung von Briefen und Fotos.** Brieftexte und Fotos werden vor der Übertragung direkt auf Ihrem lokalen Gerät verschlüsselt. Wir verfügen nur über Chiffretext und über keine Entschlüsselungsschlüssel. Folglich **können wir Ihren Brieftext oder Ihre Fotos nicht lesen, prüfen oder an Dritte weitergeben** – auch nicht bei Ermittlungen der Strafverfolgungsbehörden, bei denen nur Chiffretext bereitgestellt werden kann. Siehe Abschnitt 4.

### 2.2 Informationen, die während der Nutzung automatisch generiert werden

| Informationen | Einzelheiten | Zweck |
|---|---|---|
| Lieferstatus | Abfahrt, Reisemeilensteine, Ankunft, Rückruf, Beendigungsstatus | Stromversorgung der Postzustellungspipeline |
| Konto- und Sicherheitsstatus | Kontostatus, gegenseitige Sperrlisten, Status der Berichtsbearbeitung | Kontoverwaltung und Missbrauchsprävention |
| Handelsbuch | Bestelldaten, Münzguthaben, dauerhafter Besitz von Gegenständen, aktive Abonnements | Abrechnung, Erfüllung und Rückerstattungsabwicklung |
| Push- und Gerätetoken | Geräte-Push-Tokens und notwendige Metadaten | Versenden von Briefstatusbenachrichtigungen |
| Serviceprotokolle | API-Betriebsprotokolle, Fehlerverfolgungen und Leistungsdiagnosen | Sicherheit, Stabilität und Fehlerbehebung |

**Keine Geheimnisse in Protokollen oder Push-Benachrichtigungen.** Betriebsprotokolle enthalten niemals Brieftexte, Fotos, Einladungscodes oder genaue Koordinaten. Push-Benachrichtigungen enthalten nur generische Statusphrasen (z. B. „Ein Brief ist angekommen“) ohne persönliche Kennungen, Nachrichtentext oder Städte.

### 2.3 Was wir NIEMALS tun

- Wir greifen NICHT auf Ihre vollständige Fotobibliothek, Ihre Kontakte oder Ihren genauen GPS-Standort zu.
- Wir sammeln KEINE Tracking-Identifikatoren (IDFA/IDFV), betten KEINE Anzeigen-SDKs ein und betreiben KEINE App-übergreifende Nachverfolgung.
- Wir speisen KEINE Buchstabendaten in KI-Trainingsmodelle ein – wir haben keinen Zugriff auf Klartext;
- Wir verkaufen Ihre persönlichen Daten NIEMALS an Dritte.

## 3. Warum wir Informationen verarbeiten

| Zweck | Beteiligte Informationen | Rechtsgrundlage |
|---|---|---|
| Postzustellung und Empfang | Konto-ID, Anzeigename, Stadt, Verbindungsinformationen, verschlüsselter Brief, Lieferstatus | Erfüllung des Dienstleistungsvertrages |
| In-App-Käufe und Rückerstattungen | Kaufbuch, Abonnementgültigkeit | Erfüllung des Dienstleistungsvertrages |
| Zustellungs-Push-Benachrichtigungen | Push-Token, Auslieferungszustand | Ihre Einwilligung (jederzeit widerrufbar) |
| Sicherheit, Missbrauchsprävention und Meldungen | Sicherheitsstatus, Berichtsdetails, Betriebsprotokolle | Berechtigtes Interesse und rechtliche Verpflichtung |
| Diagnose und Servicestabilität | Betriebsprotokolle | Berechtigtes Interesse |
| Umgang mit Benutzerrechten und Anfragen | Von Ihnen bereitgestellte Informationen | Gesetzliche Verpflichtung |

## 4. Ende-zu-Ende-Verschlüsselung

Dies ist die wichtigste technische Schutzmaßnahme von Detour Post:

**Die Verschlüsselung erfolgt lokal auf Ihrem Gerät.** Wenn Sie auf „Diesen Brief versiegeln“ tippen, werden alle Texte und Fotos vor der Übertragung auf Ihrem Gerät verschlüsselt. Die Entschlüsselungsschlüssel liegen ausschließlich bei Ihnen und dem von Ihnen benannten Empfänger.

**Wir speichern nur Chiffretext.** Unsere Server speichern nur verschlüsselte Blobs. Wir bewahren keine Entschlüsselungsschlüssel in irgendeiner Form auf und bieten auch keine manuelle Schlüsselwiederherstellung an.

**Keine Ausnahmen.** Wir unterhalten keine administrativen Hintertüren, Kanäle zur Inhaltsüberprüfung oder Außerkraftsetzungen des Kundendienstes. Da wir keinen Klartext anzeigen können, können wir keine automatische Schlüsselwortfilterung oder Inhaltsempfehlung durchführen.

**Implikationen:**
- Nur Sie können den Inhalt vor der Lieferung sehen;
- Nur Sie und Ihr Empfänger können den Inhalt nach der Zustellung sehen;
- Wenn Sie Ihr Gerät verlieren und kein persönliches iCloud-Backup haben, können wir Ihre Briefe nicht wiederherstellen – wir haben nicht die Schlüssel;
- Sicherheitsberichte lösen Beziehungssperren und Kontostrafen aus, ohne dass menschliche Mitarbeiter den Inhalt der Briefe lesen.

**Persönliches Backup.** Briefdatensicherungen erfolgen ausschließlich über Ihre persönliche iCloud, sofern diese aktiviert ist. Backups befinden sich vollständig in Ihrem Apple-ID-Ökosystem. Wir haben keinen Zugriff auf Ihr iCloud-Backup oder Ihre Schlüsselbundschlüssel.

## 5. Systemberechtigungen

Die App fordert nur eine Systemberechtigung an:

| Erlaubnis | Auf Anfrage | Zweck |
|---|---|---|
| Benachrichtigungen | Wenn Sie sich für Briefbenachrichtigungen entscheiden | Benachrichtigt Sie, wenn Briefe abgehen oder ankommen. Nutzlasten enthalten nur generische Phrasen |

Das Deaktivieren von Benachrichtigungen hat keinen Einfluss auf das Senden oder Empfangen von Briefen.

**Berechtigungen, die wir NICHT anfordern:**
- **Fotos:** Die Fotoauswahl verwendet die systemeigene Fotoauswahl. Nur das einzelne ausgewählte Bild wird an die App übergeben; Ein vollständiger Zugriff auf die Fotobibliothek ist weder erforderlich noch erforderlich.
- **Standort:** Städte werden manuell aus einer Liste ausgewählt. Wir verfolgen niemals Ihre Gerätekoordinaten.
- **Kontakte, Kamera, Mikrofon, App-Tracking (ATT):** Nicht angefordert und kein entsprechender Code vorhanden.

## 6. Dritte

Wir verkaufen niemals personenbezogene Daten. Die Informationen werden ausschließlich an die erforderlichen Infrastrukturanbieter weitergegeben:

| Drittanbieter | Verarbeitete Daten | Zweck | Notizen |
|---|---|---|---|
| Apfel | Konto-ID, StoreKit-Käufe, Push-Versand, MapKit-Geokodierung | Authentifizierung, In-App-Abrechnung, Benachrichtigungen, Kartenanzeige | Vorbehaltlich der [Datenschutzrichtlinie von Apple](https://www.apple.com/legal/privacy/) |
| Google | Konto-ID | Optionale Authentifizierung | Es gelten die [Datenschutzbestimmungen von Google](https://policies.google.com/privacy) |
| Apple Push Notification Service (APNs) | Push-Token, generische Warnungsnutzlast | Benachrichtigungsversand | Payloads enthalten keinen Brieftext oder Empfängeridentitäten |
| Cloud-Infrastrukturanbieter | Verschlüsselte Brief-Blobs, Kontobuch | Cloud-Computing und sichere Speicherung | Die Verarbeitung erfolgt streng nach unserer Weisung |

Die iOS-App enthält keine Tracking-, Werbe- oder Analyse-SDKs von Drittanbietern.

## 7. Datenspeicherung und internationale Übermittlungen

- **Auf Ihrem Gerät:** Lokale Briefe, Entwürfe und Einstellungen.
- **In Ihrer persönlichen iCloud:** Verschlüsselte Datenbanksicherungen in Ihrem privaten Apple-Konto.
- **Auf unseren Servern:** Konto-IDs, Anzeigenamen, verschlüsselte Briefnutzdaten und Transaktionsbücher, die in einer sicheren Cloud-Infrastruktur im Ausland gespeichert sind. Daten können im Rahmen strenger vertraglicher Garantien international übertragen und verarbeitet werden.

## 8. Datenaufbewahrungsfristen

| Informationen | Aufbewahrungsfrist |
|---|---|
| Geburtsdatum | Nicht gespeichert. Einmal bei der Registrierung ausgewertet und sofort entsorgt |
| Konto-ID, Anzeigename, Stadt, Verbindungen | Dauer des Kontolebenszyklus; bei Löschung des Kontos gelöscht oder unwiderruflich anonymisiert |
| Buchstaben-Chiffretext | Wird sofort nach Bestätigung der Zustellung durch den Empfänger gelöscht; nicht abgeholte Briefe nach 90 Tagen bereinigt |
| Einkaufsbuch | Wird gemäß den Finanz-, Steuer- und Verbraucherschutzgesetzen aufbewahrt |
| Push-Token | Wird sofort nach der Abmeldebenachrichtigung oder der Löschung des Kontos von den Servern entfernt |
| Serviceprotokolle | Wird für ein kurzes Diagnosefenster aufbewahrt und automatisch gelöscht. Enthält keine privaten Geheimnisse |

## 9. Ihre Datenschutzrechte

Sie können die folgenden Rechte in Bezug auf Ihre personenbezogenen Daten ausüben:

| Richtig | So trainieren Sie |
|---|---|
| Zugriff und Portabilität | Profil, Käufe und Vermögenswerte unter „Mein Profil“ anzeigen; Export anfordern über detourpost@aivolo.studio |
| Berichtigung | Bearbeiten Sie den Anzeigenamen und die Stadt in den Profileinstellungen. Kontaktieren Sie uns für weitere Unterlagen |
| Löschung | Nutzen Sie die In-App-Funktion „Konto löschen“ oder kontaktieren Sie uns für spezifische Datenanfragen |
| Einwilligung widerrufen | Deaktivieren Sie Benachrichtigungen in den App-Einstellungen oder iOS-Systemeinstellungen |
| Kontolöschung | Navigieren Sie zu „Mein Profil“ → „Kontolöschung und -isolierung“ → „Konto löschen“ |
| Fragen & Anfragen | Kontaktieren Sie detourpost@aivolo.studio |

**Was passiert bei der Löschung des Kontos:** Nicht ausgeschiedene Briefe werden beendet; abgegangene Briefe gelangen weiter an ihren Bestimmungsort; Profildatensätze, Blockbeziehungen und Gerätetokens werden sofort und dauerhaft gelöscht.

Wir antworten auf alle Datenschutzanfragen innerhalb von **48 Stunden**.

## 10. Minderjährige

Die App ist für Benutzer ab 13 Jahren gedacht (oder älter, abhängig von den Anforderungen der örtlichen Rechtsprechung). Wir erfassen wissentlich keine personenbezogenen Daten von Minderjährigen unter dem geltenden Registrierungsalter. Wenn Sie glauben, dass sich ein Minderjähriger ohne Genehmigung registriert hat, wenden Sie sich an detourpost@aivolo.studio und wir werden das Konto umgehend löschen.

## 11. Sicherheitsmaßnahmen

- Ende-zu-Ende-Verschlüsselung für Brieftexte und Fotos;
- Verschlüsselte Transportkanäle (TLS/HTTPS);
- Anmeldeinformationen und Schlüssel, die im sicheren Systemspeicher (iOS-Schlüsselbund) gespeichert sind;
- Prinzip der geringsten Rechte für die Serverinfrastruktur;
- Kontinuierliche Schwachstellenprüfung und Konfigurationsprüfungen.

## 12. Richtlinienaktualisierungen

Wir können diese Datenschutzrichtlinie regelmäßig aktualisieren. Wesentliche Änderungen werden deutlich sichtbar in der App angezeigt. Wenn Sie mit den geänderten Bedingungen nicht einverstanden sind, können Sie Ihr Konto löschen.

## 13. Kontaktieren Sie uns und Beschwerden

- **Betreiber:** Yong Wang
- **E-Mail:** detourpost@aivolo.studio

Wir beantworten Anfragen innerhalb von **48 Stunden**. Sie haben außerdem das Recht, eine Beschwerde bei Ihrer örtlichen Datenschutzaufsichtsbehörde einzureichen.

---

© 2026 Yong Wang. Alle Rechte vorbehalten.