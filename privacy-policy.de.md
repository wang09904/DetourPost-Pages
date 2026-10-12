# Datenschutzerklärung für Detour Post

**Interner Prüfentwurf · aktualisiert am 6. Oktober 2026 · nicht veröffentlicht und nicht wirksam · rechtliche und sprachliche Prüfung läuft.**

---

## 1. Einführung

Detour Post wird von Yong Wang als Einzelperson betrieben. Yong Wang bestimmt als Verantwortlicher, wie personenbezogene Daten für den Dienst verarbeitet werden.

In dieser Datenschutzrichtlinie wird erklärt, welche Informationen wir sammeln, warum wir sie verarbeiten, wie sie gehandhabt und gespeichert werden, welche Aufbewahrungsfristen es gibt und wie Sie Ihre Datenschutzrechte ausüben können.

Unser Grundprinzip ist einfach: **Ihre Briefe sind zwischen Ihnen und Ihrem Empfänger privat. Wir können sie nicht lesen und haben auch nicht die Absicht, sie zu lesen.**

## 2. Informationen, die wir verarbeiten

### 2.1 Informationen, die Sie aktiv bereitstellen

| Informationen | Einzelheiten | Notwendigkeit |
|---|---|---|
| Konto und Anmeldeidentität | Konto-ID, Kennung des Anmeldedienstes und bestätigte E-Mail-Adresse von Apple oder Google | Für die Erstellung und Authentifizierung des Kontos erforderlich |
| Anmeldedaten | Sitzungstoken; der Dienst speichert einen Hashwert jedes Tokens | Für sicheren Zugriff erforderlich |
| Monat und Jahr der Geburt sowie ausgewählte Region | Die App prüft die Altersberechtigung auf Ihrem Gerät anhand des von Ihnen eingegebenen Geburtsmonats und -jahrs sowie der ausgewählten Region | Für die Registrierung erforderlich. Monat und Jahr bleiben in den kontobezogenen App-Daten auf Ihrem Gerät und können im Profil eingesehen und geändert werden; sie werden nicht an unsere Server gesendet oder dort gespeichert. Der Dienst speichert die angewandte Regelversion und die Anmelderegion |
| Anzeigename | Name, den Personen sehen, mit denen Sie Briefe austauschen | Für die Registrierung erforderlich; später im Profil änderbar |
| Stadt | Die zum Versenden gewählte Stadt einschließlich der von der App gespeicherten Ortsangaben | Für die Registrierung und das Versenden erforderlich |
| Verbindungsinformationen | Beziehungsstatus, Einladungscodes und Brief-Abholcodes | Zum Austausch von Briefen erforderlich |
| Briefinhalt | Brieftext, gewähltes Briefpapier und Dekorationen, beigefügte Fotos, Kurier und gewählte oder geplante Zustellzeit | Entsteht nur, wenn Sie einen Brief versenden |
| Meldungsdaten | IDs des meldenden und des gemeldeten Kontos; Art, Quelle und ID des Ziels; gewählter Grund; Zuordnungs-ID für die Protokollierung; Status und Erstellungszeit. **Enthält keinen Brieftext, keine Fotos, keinen Freitext und keine Koordinaten.** Eine Meldung blockiert zugleich die gemeldete Person und beendet deren noch nicht zugestellte Briefe an Sie | Entsteht nur, wenn Sie eine Meldung einreichen |
| Private Notizen | Notizen, die Sie zu einem Kontakt schreiben | Optional. Auf Ihrem Gerät gespeichert und nur bei aktivierter persönlicher iCloud-Sicherung in dieser enthalten; nicht an unseren Dienst hochgeladen |

**Ende-zu-Ende-Verschlüsselung von Briefen und Fotos.** Brieftext und Fotos werden auf Ihrem Gerät verschlüsselt, bevor sie an unseren Dienst gesendet werden. Für diese Inhalte halten wir nur Chiffretext und keine Entschlüsselungsschlüssel. Die in dieser Erklärung genannten Konto- und Dienstdaten werden gesondert verarbeitet. Siehe Abschnitt 4.

### 2.2 Informationen, die während der Nutzung automatisch generiert werden

| Informationen | Einzelheiten | Zweck |
|---|---|---|
| Zustellstatus | Start, Reiseereignisse, Ankunft, Rückruf und Beendigung | Briefe versenden und zustellen |
| Konto- und Sicherheitsstatus | Kontostatus, gegenseitige Sperrlisten, Status der Berichtsbearbeitung | Kontoverwaltung und Missbrauchsprävention |
| Kauf- und Bestandsdaten | Bestellungen, Coin-Buchungen und -Guthaben, Bestände an Briefmarken und Einheiten zur Planung der Zustellzeit, dauerhafter Artikelbesitz, Mitgliedschaften und Status der Kaufwiederherstellung | Abrechnung, Erfüllung, Wiederherstellung und Rückerstattung |
| Push- und Gerätetoken | Geräte-Push-Tokens und notwendige Metadaten | Versenden von Briefstatusbenachrichtigungen |
| Serviceprotokolle | API-Betriebsprotokolle, Fehlerverfolgungen und Leistungsdiagnosen | Sicherheit, Stabilität und Fehlerbehebung |

**Push-Benachrichtigungen.** Der sichtbare Hinweis verwendet allgemeine Formulierungen. Die Nutzlast enthält außerdem eine Benachrichtigungskategorie und eine undurchsichtige Ereignis-ID zum Öffnen der passenden App-Seite; sie enthält keinen Brieftext, keine Fotos und keine Ortsangaben. Betriebsprotokolle können technische Anfrage- oder Fehlerdetails enthalten; siehe Abschnitt 8.

### 2.3 Was wir NIEMALS tun

- Wir greifen NICHT auf Ihre vollständige Fotobibliothek, Ihre Kontakte oder Ihren genauen GPS-Standort zu.

- Wir verwenden Werbe-IDs (IDFA/IDFV) weder für gezielte Werbung noch für App-übergreifendes Tracking und binden kein Werbe-SDK ein.

- Wir verwenden keine Briefdaten zum Training von KI-Modellen – wir haben keinen Zugriff auf Klartext;

- Wir verkaufen Ihre persönlichen Daten NIEMALS an Dritte.

## 3. Warum wir Informationen verarbeiten

| Zweck | Verarbeitete Informationen |
|---|---|
| Briefe senden und empfangen | Konto-ID, Anzeigename, Stadt, Verbindungsdaten, verschlüsselte Briefe und Zustellstatus |
| In-App-Käufe, Erfüllung und Rückerstattungen | Kauf- und Vermögensbuchungen sowie Mitgliedschaftsstatus |
| Zustellbenachrichtigungen | Push-Token und Zustellstatus |
| Sicherheit, Meldungen und Missbrauchsprävention | Sicherheits- und Kontostatus, Meldungsdaten und Betriebsprotokolle |
| Fehlerbehebung und Stabilität | Betriebsprotokolle |
| Anfragen zu Rechten und Beschwerden | Informationen, die Sie uns übermitteln |

Die Rechtsgrundlage für jede Verarbeitung hängt vom anwendbaren Recht und den Umständen der jeweiligen Verarbeitung ab. In diesem Entwurf ist noch keine Rechtsgrundlage jedem Zweck zugeordnet. Diese Prüfung muss vor der Veröffentlichung abgeschlossen werden; wir stützen uns nicht auf eine Rechtsgrundlage, die nach dem einschlägigen Recht nicht anwendbar ist.

## 4. Ende-zu-Ende-Verschlüsselung

Dies ist die wichtigste technische Schutzmaßnahme von Detour Post:

**Die Verschlüsselung erfolgt lokal auf Ihrem Gerät.** Wenn Sie auf „Diesen Brief versiegeln“ tippen, werden alle Texte und Fotos vor der Übertragung auf Ihrem Gerät verschlüsselt. Die Entschlüsselungsschlüssel liegen ausschließlich bei Ihnen und dem von Ihnen benannten Empfänger.

**Brieftexte und Fotos speichern wir nur verschlüsselt.** Wir besitzen keine Entschlüsselungsschlüssel für diese Inhalte und bieten keine manuelle Schlüsselwiederherstellung an. Daneben verarbeiten wir die in dieser Erklärung beschriebenen Konto- und Dienstdaten.

**Keine Ausnahmen.** Wir unterhalten keine administrativen Hintertüren, Kanäle zur Inhaltsüberprüfung oder Ausnahmen, die dem Kundendienst Zugriff auf Briefinhalte ermöglichen. Da wir keinen Klartext anzeigen können, können wir keine automatische Schlüsselwortfilterung oder Inhaltsempfehlung durchführen.

- Nur Sie können den Inhalt vor der Lieferung sehen;

- Nur Sie und Ihr Empfänger können den Inhalt nach der Zustellung sehen;

- Wenn Sie Ihr Gerät verlieren und kein persönliches iCloud-Backup haben, können wir Ihre Briefe nicht wiederherstellen – wir haben nicht die Schlüssel;

- Eine Sicherheitsmeldung erfasst den gewählten Grund und zugehörige Konto- oder Brief-IDs, bewirkt eine gegenseitige Blockierung und beendet noch nicht zugestellte Briefe der gemeldeten Person an Sie. Sie legt keinen Briefinhalt offen. Wenn Yong Wang von der Meldung Kenntnis erhält, bemüht er sich in angemessenem Umfang um eine Prüfung und gegebenenfalls geeignete Maßnahmen. Eine feste Prüfungs- oder Antwortfrist wird nicht zugesagt; weitere Kontomaßnahmen setzen eine Prüfung voraus.

**Persönliche Sicherung.** Wenn Sie sie aktivieren, werden ausgewählte Posttaschendaten – einschließlich privater Kontaktnotizen, Entwürfe, noch ausstehender Einladungsdaten und gespeicherter Briefe – auf Ihrem Gerät verschlüsselt und über CloudKit in Ihrer persönlichen iCloud gesichert. Der Sicherungsschlüssel liegt im Schlüsselbund Ihres Geräts. Nach Überprüfung einer Sicherung wird ein Wiederherstellungsschlüssel im iCloud-Schlüsselbund gespeichert, damit er auf Ihren anderen Apple-Geräten verfügbar sein kann. Wir erhalten keinen der beiden Schlüssel und können die Sicherung nicht entschlüsseln.

## 5. Systemberechtigungen

Die App kann nach dem ersten versendeten oder empfangenen Brief um die Benachrichtigungsberechtigung bitten; Sie können sie auch in den Einstellungen anfordern. Wenn Sie eine erzeugte Reisendenkarte in der Fotomediathek speichern möchten, fordert die App eine Berechtigung ausschließlich zum Hinzufügen von Fotos an.

| Erlaubnis | Auf Anfrage | Zweck |
|---|---|---|
| Benachrichtigungen | Nach dem ersten versendeten oder empfangenen Brief oder beim Aktivieren in den Einstellungen | Allgemeiner sichtbarer Hinweis; die Nutzlast enthält zusätzlich eine Kategorie und eine undurchsichtige Ereignis-ID zum Öffnen der passenden App-Seite, aber keinen Brieftext und keine Ortsangaben |
| Fotos (nur hinzufügen) | Wenn Sie eine erzeugte Reisendenkarte speichern möchten | Speichert dieses Bild; erlaubt kein Durchsuchen Ihrer Fotomediathek |

Die App synchronisiert Ihre Benachrichtigungseinstellungen mit dem Dienst, der damit entscheidet, welche Hinweise gesendet werden. Die iOS-Berechtigung steuert, ob Hinweise auf dem Gerät erscheinen können. Keine dieser Einstellungen löscht oder deaktiviert für sich allein den Gerätetoken beim Dienst. Das Ablehnen einer optionalen Berechtigung verhindert für sich allein nicht das grundlegende Senden oder Empfangen.

**Weitere Hinweise zu Berechtigungen:**

- **Fotos:** Beim Anhängen eines Fotos gibt die systemeigene Auswahl nur das von Ihnen gewählte Bild an die App weiter. Die App durchsucht nicht Ihre gesamte Fotomediathek. Zum Speichern einer erzeugten Reisendenkarte verwendet sie die separate Berechtigung zum Hinzufügen von Fotos und den dazugehörigen Systemdialog.

- **Standort:** Sie wählen die Stadt für jeden Brief. Wir erfassen nicht den Gerätestandort und verfolgen keine Bewegungen. Die App enthält einen begrenzten Katalog mit Länder- und Städtenamen sowie Koordinaten für lokale Suchvorschläge, begrenzte Offline-Ergebnisse und Kartenbeschriftungen. Zuerst wird dieser Katalog durchsucht; ein Treffer wird lokal verwendet und der Suchbegriff nicht an MapKit gesendet. Ohne Treffer fragt die App Apple MapKit nach Orten. Fehlt im Katalog ein Mittelpunkt für das ausgewählte Land oder Gebiet, kann die App dessen Namen über Core Location an Apple senden, um die Karte auszurichten. Ein Kartenpunkt wird ebenfalls mit Core Location umgekehrt geocodiert. Ist Apples Ergebnis nicht verfügbar, kann eine nahegelegene Katalogstadt als begrenzte Ersatzlösung dienen. Apple erhält dabei den Suchtext, den Länder- oder Gebietsnamen oder die Koordinaten des Kartenpunkts. Dafür ist keine Standortberechtigung erforderlich.

- **Kontakte, Kamera, Mikrofon, App-Tracking (ATT):** Nicht angefordert und kein entsprechender Code vorhanden.

## 6. Dritte

Wir verkaufen keine personenbezogenen Daten. Die für die genutzten Funktionen erforderlichen Dienstanbieter verarbeiten entsprechende Daten. Bei serverseitiger Speicherung und Verarbeitung von Brieftexten und Fotos erhalten sie Chiffretext; wir stellen ihnen keine Entschlüsselungsschlüssel bereit.

| Drittanbieter | Verarbeitete Daten | Zweck | Notizen |
|---|---|---|---|
| Apple | Anmeldekennung und bestätigte E-Mail-Adresse, In-App-Käufe und Abonnements, Push-Token und Benachrichtigungszustellung, verschlüsselte persönliche iCloud-Backups und Wiederherstellungsschlüssel (falls aktiviert), Suchbegriffe für MapKit-Ortssuchen, Länder- oder Gebietsnamen zur Kartenausrichtung, wenn dem Katalog ein Mittelpunkt fehlt, sowie Kartenkoordinaten für die Core-Location-Geocodierung | Anmeldung, Abrechnung, Benachrichtigungen, Backup und Karten-/Suchfunktionen | Es gilt die [Datenschutzerklärung von Apple](https://www.apple.com/legal/privacy/) |
| Google | Kennung des Anmeldedienstes und bestätigte E-Mail-Adresse, sofern bereitgestellt | Anmeldung, wenn Sie Google wählen | Es gilt die [Datenschutzerklärung von Google](https://policies.google.com/privacy) |
| Apple Push Notification service (APNs) | Push-Token, allgemeiner Hinweistext, Benachrichtigungskategorie und undurchsichtige Ereignis-ID | Zustellung von Benachrichtigungen | Kein Brieftext, keine Fotos und kein genauer Standort in der Nutzlast |
| Cloudflare | Verschlüsselte Briefdaten, Konto- und Anmeldedaten, gewählte Stadtdaten, Kauf- und Zustellaufzeichnungen, Push-Token und Dienstprotokolle | Cloud-Berechnung, Datenbank und Objektspeicherung | Es gilt die [Datenschutzerklärung von Cloudflare](https://www.cloudflare.com/privacypolicy/) |

Die iOS-App enthält keine Tracking-, Werbe- oder Analyse-SDKs von Drittanbietern.

## 7. Datenspeicherung und internationale Übermittlungen

- **Auf Ihrem Gerät:** Briefe, Entwürfe, private Kontaktnotizen und Einstellungen.

- **In Ihrer persönlichen iCloud:** Wenn aktiviert, eine verschlüsselte Sicherung ausgewählter Posttaschendaten, darunter private Kontaktnotizen, Entwürfe, ausstehende Einladungsdaten und gespeicherte Briefe.

- **Auf unseren Servern:** Konto- und Anmeldekennungen, bestätigte E-Mail-Adresse, Anzeigenamen, gespeicherte Angaben zur gewählten Stadt, Beziehungs- und Zustellaufzeichnungen, verschlüsselte Briefinhalte, Kaufaufzeichnungen, Push-Token und Dienstprotokolle. Unsere Cloud-Infrastruktur befindet sich außerhalb der Länder oder Regionen mancher Nutzer; diese Daten können daher international verarbeitet werden.

## 8. Datenaufbewahrungsfristen

| Information | Speicherdauer |
|---|---|
| Geburtsmonat und -jahr | In kontobezogenen App-Daten auf Ihrem Gerät gespeichert und im Profil einsehbar und änderbar; nicht an unsere Server übermittelt oder dort gespeichert |
| Konto und Anmeldeidentität | Bei Kontolöschung werden das Konto deaktiviert, Sitzungen widerrufen sowie Profil- und Benachrichtigungsdaten entfernt. Der aktuelle Dienstentwurf behält den Datensatz des gelöschten Kontos und die Anmeldeanbieter-ID; eine feste Löschfrist ist noch nicht festgelegt. |
| Verschlüsselte Briefinhalte | Nach vollständiger Speicherbestätigung durch das Gerät des Empfängers beginnt die serverseitige Bereinigung der verschlüsselten Briefinhalte. Ohne diese Bestätigung wird der Brief 90 Tage nach dem Zeitpunkt, zu dem er für den Empfänger verfügbar wird, unzugänglich und zur Bereinigung vorgemerkt. Bei terminierten Briefen beginnt diese Frist mit der festgelegten Zustellzeit. Auch nach Ablauf dieser Frist wird ein gelöschtes Absenderkonto nicht wiederhergestellt. |
| Kauf- und Erfüllungsdaten | Zur Abwicklung von Käufen, Rückerstattungen und bereits begonnenen Zustellungen. Eine feste Aufbewahrungsfrist ist noch nicht festgelegt. |
| Push-Token | In-App-Benachrichtigungseinstellungen steuern, welche Hinweise gesendet werden; die iOS-Berechtigung steuert ihre Anzeige auf dem Gerät. Bei Kontolöschung wird der Geräte-Token entfernt; von APNs als ungültig gemeldete Token werden deaktiviert. |
| Sicherheitsmeldungen | Grund, verknüpfte Konto- oder Brief-ID, Status und Erstellungszeit. Feste Aufbewahrungsfrist und Löschkriterium sind noch nicht festgelegt. |
| Betriebsprotokolle | Können für Sicherheit, Zuverlässigkeit und Fehlerbehebung erstellt werden und technische Anfragen oder Fehlerdetails enthalten. Eine feste Frist ist noch nicht festgelegt. |

Die Aufbewahrungsfristen oder Löschkriterien für gelöschte Konten und Anbieter-IDs, Kauf- und Erfüllungsdaten, Sicherheitsmeldungen sowie Betriebsprotokolle sind noch nicht abschließend festgelegt. Diese Regeln und die Rechtsgrundlage je Verarbeitungszweck müssen vor Veröffentlichung geklärt werden.

## 9. Ihre Datenschutzrechte

Je nach Ihrem Wohnort kann Ihnen das anwendbare Recht Rechte auf Auskunft, Berichtigung, Löschung oder eine Kopie personenbezogener Daten, auf Widerspruch oder Einschränkung bestimmter Verarbeitungen sowie auf Widerruf einer Einwilligung gewähren. Diese Erklärung beschränkt keine Ihnen gesetzlich zustehenden Rechte. Richten Sie Anfragen an detourpost@aivolo.studio; wir können Angaben benötigen, um Ihre Identität zu prüfen.

| Recht | So üben Sie es aus |
|---|---|
| Auskunft oder Kopie | Unter „Ich“ können Sie Kontodaten, Käufe und Bestände einsehen; für Anfragen, die die App nicht unterstützt, kontaktieren Sie uns |
| Berichtigung | Unter „Ich“ → „Profil“ können Sie Anzeigename und Stadt ändern; für andere Daten kontaktieren Sie uns |
| Löschung | Nutzen Sie die In-App-Funktion „Konto löschen“ oder kontaktieren Sie uns für spezifische Datenanfragen |
| Einwilligung widerrufen | Schreiben Sie an detourpost@aivolo.studio, wenn Sie eine Einwilligung für eine darauf beruhende Verarbeitung widerrufen möchten; die Wirkung auf frühere Verarbeitungen richtet sich nach dem anwendbaren Recht |
| Kontolöschung | „Ich“ → „Konto löschen“ → „Konto löschen“ |
| Fragen & Anfragen | Kontaktieren Sie detourpost@aivolo.studio |

**Bei einer Kontolöschung:** Das Konto wird deaktiviert, seine Sitzungen werden widerrufen und Profil- sowie Benachrichtigungsdaten werden entfernt. Noch nicht gestartete Sendungen enden; bereits gestartete Briefe werden nach dem bestehenden Plan weiter zugestellt. Die Löschung des App-Kontos beendet keine über Apple abgerechnete Mitgliedschaft; verwalten oder kündigen Sie diese in den Abonnementeinstellungen Ihres Apple-Accounts. Der aktuelle Dienst behält einen Datensatz des gelöschten Kontos und die Anmeldeanbieter-ID; siehe Abschnitt 8.

Wir bearbeiten Anfragen nach Maßgabe des anwendbaren Rechts. Die Bearbeitungsdauer hängt von Art und Umfang der Anfrage ab; eine allgemeine Frist sagen wir nicht zu.

## 10. Minderjährige

Die App richtet sich an Personen, die mindestens 16 Jahre alt sind (in Korea mindestens 15 Jahre); in manchen Regionen kann ein anderes Mindestalter gelten. Bei der Registrierung prüft die App auf Ihrem Gerät anhand Ihres Geburtsmonats und -jahrs sowie der ausgewählten Region, ob Sie die dort geltenden Altersvoraussetzungen erfüllen. Der Geburtsmonat und das Geburtsjahr bleiben in den App-Daten auf Ihrem Gerät und werden nicht an unsere Server gesendet oder dort gespeichert.

Wenn Sie vermuten, dass jemand das geltende Mindestalter nicht erreicht, schreiben Sie an detourpost@aivolo.studio. Wenn Yong Wang davon Kenntnis erhält, wird er sich in angemessenem Umfang bemühen, den Hinweis zu prüfen und die nach anwendbarem Recht erforderlichen Schritte zu ergreifen. Eine feste Prüf- oder Antwortfrist wird nicht zugesagt. Erziehungsberechtigte können sich ebenfalls an diese Adresse wenden.

## 11. Sicherheitsmaßnahmen

- Ende-zu-Ende-Verschlüsselung für Brieftexte und Fotos;

- Verschlüsselte Transportkanäle (TLS/HTTPS);

- Anmeldeinformationen und Schlüssel, die im sicheren Systemspeicher (iOS-Schlüsselbund) gespeichert sind;

- Geräteschutz für lokal gespeicherte Zugangsdaten und Verschlüsselungsschlüssel.

Keine Sicherheitsmaßnahme kann absolute Sicherheit garantieren. Bei einem Datensicherheitsvorfall informieren wir und ergreifen Maßnahmen, soweit dies nach anwendbarem Recht erforderlich ist.

## 12. Richtlinienaktualisierungen

Wir können diese Datenschutzerklärung aktualisieren. Der aktuelle Text und das Aktualisierungsdatum stehen auf dieser Seite. Wir verwenden personenbezogene Daten nicht für Zwecke, die mit den hier beschriebenen unvereinbar sind. Soweit das anwendbare Recht eine Mitteilung über wesentliche Änderungen oder eine neue Datennutzung verlangt, informieren wir auf geeignete Weise.

## 13. Kontaktieren Sie uns und Beschwerden

- **Betreiber:** Yong Wang

- **E-Mail:** detourpost@aivolo.studio

Bei Fragen oder Beschwerden schreiben Sie an detourpost@aivolo.studio. Wenn Yong Wang von Ihrer Nachricht Kenntnis erhält, bemüht er sich in angemessenem Umfang um eine Prüfung und gegebenenfalls eine Antwort. Eine bestimmte Antwortfrist wird nicht zugesagt. Sie können sich auch an eine für Ihre Angelegenheit zuständige Datenschutzaufsichtsbehörde wenden.
