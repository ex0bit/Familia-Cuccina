# Konzept: @familie.cuccina

**Gruppe 08 ... Falk und Jens**
Projektarbeit26 ... Interaktive Museumsinstallation zu Paolo Veroneses „Die Madonna der Familie Cuccina“ (um 1571)

---

## 1. Leitidee

Das Gemälde war schon 1571 ein Statement: Die Familie Cuccina zeigt sich mit der Madonna, mit Tugenden, in kostbaren Stoffen. Das Kleid der Mutter ist mit Cochenille gefärbt, genau dem Farbstoff, mit dem die Familie ihr Geld verdient. Heute würde man so etwas posten.

**@familie.cuccina** erzählt die Geschichte des Bildes und der Familie als **Social-Media-Welt im Stil von Instagram**. Jede Person aus dem Bild und aus ihrem Umfeld hat ein eigenes Profil. Posts und Kommentare erzählen die Geschichte historisch, und die Beziehungen der Personen werden über den Ton der Kommentare spürbar: Freunde schicken Herzen und Lob, Rivalen liefern sich „beefy“ Kommentare.

Die Anwendung ist **rein virtuell**: eine Web-Oberfläche auf einem Screen im Museum (oder im Browser), ohne Kamera und ohne Fotos von Besuchern.

---

## 2. Bezug zur Aufgabe und zu den Personas

**Leitfrage des Kurses:** Wie machen wir das Gemälde und die Geschichte der Familie Cuccina interaktiv, verständlich und für unterschiedliche Besuchergruppen erreichbar?

| Persona-Typ | Bedürfnis | Antwort von @familie.cuccina |
|---|---|---|
| **Recharger** (schaut lieber, liest ungern lange Texte) | „Ich möchte nicht alles lesen müssen.“ | Kurze Posts und Kommentare statt Infotafeln, viel Bild, wenig Text |
| **Facilitator** (mit Kindern unterwegs) | „Ich möchte nach dem Besuch etwas Neues verstanden haben.“ | Bekanntes Format, das Kinder und Erwachsene sofort bedienen können, Humor als Einstieg |
| **Explorer** (will selbst entdecken) | Eigene Wege, Zusammenhänge finden | Freies Springen von @Name zu @Name, die Geschichte setzt sich aus Puzzleteilen zusammen |

**Abgrenzung zu den anderen Gruppen:** Mehrere Gruppen arbeiten mit „Figur anklicken, Info lesen“ (Gruppe 01, Gruppe 04) oder mit Restaurierung, Röntgen und Lupe (Gruppe 03, 04, 05). Unser Ansatz erzählt die Inhalte **über Beziehungen und Emotionen** statt über Infoboxen. Das Anklicken von Figuren bleibt als Einstieg (Variante B), ist aber nur der Anfang.

---

## 3. Grundregeln der Inhalte

- Jede Person (Familie und Dritte) hat ein **eigenes Profil**.
- Jedes Profil hat **5 Posts**, chronologisch sortiert.
- Jeder Post hat **5 Kommentare** von anderen Profilen.
- Jeder **@Name** in einem Kommentar ist klickbar und führt zum Profil dieser Person.
- **Posts und Kommentare erzählen die Geschichte historisch.** Auch Alltägliches ist erlaubt (z. B. was die Mutter gestern gegessen hat: Steak oder doch nur Brot und ein Krug Wein), solange es in die Zeit passt und etwas über Stand, Reichtum oder Alltag verrät.
- **Der Ton zeigt die Beziehung:**
  - Mögen sich: Herzen, Lob, liebevolle Worte
  - Mögen sich nicht: spitze, „beefy“ Kommentare
- Jeder Post trägt Ort und Jahr (z. B. „Venedig, 1571“), damit man sich zeitlich orientieren kann, egal wo man einsteigt.

---

## 4. Ablauf und Informationsarchitektur

```
Startscreen (3x3 Grid, 9 zufällige Posts)
        │  Klick auf einen Post
        ▼
Zoom-Übergang in den Post
        │
        ▼
Post-Ansicht im Feed (Bild, Caption, 5 Kommentare)
        │  Klick auf @Name
        ▼
Profil der Person (Bio, Highlights, 5 Posts chronologisch)
        │  Klick auf einen Post / @Name
        ▼
... beliebig weiter durch das Netzwerk
```

**Startscreen:** Wie die Explore-Seite von Instagram. Ein 3x3 Grid mit 9 zufällig ausgewählten Posts aus allen Profilen. Bei jedem Neustart (bzw. nach Inaktivität im Museum) wird neu gemischt.

**Zoom-Übergang:** Der angeklickte Post zoomt aus dem Grid heraus und füllt den Screen. Man ist „drin“ im Feed.

**Feed und Profil:** Im Post stehen Caption und 5 Kommentare. Über die @Namen wechselt man ins Profil. Profile laufen chronologisch, das Grid darf zufällig sein.

**Zurück:** Ein Home-Button führt jederzeit zurück zum Grid.

---

## 5. Zwei Varianten (Ergebnis laut Aufgabe: Konzept mit 2 Varianten)

### Variante A ... Explore-Grid

Einstieg über das 3x3 Grid mit zufälligen Posts (siehe oben).

| Vorteile | Nachteile |
|---|---|
| Sofort vertraut, niedrige Einstiegshürde | Gemälde ist anfangs nur ein Post unter vielen |
| Jeder Besuch fühlt sich anders an | Einstieg ohne roten Faden, Zusammenhang entsteht erst beim Weiterklicken |
| Neugier durch Vorschaubilder | |

### Variante B ... Einstieg über das Gemälde

Der Startscreen zeigt das Gemälde. Die Personen im Bild sind markiert wie getaggte Personen in einem Foto. Ein Tap auf eine Figur öffnet deren Profil, von dort geht es wie in Variante A weiter.

| Vorteile | Nachteile |
|---|---|
| Das Original steht im Mittelpunkt | Nähe zu den Ideen von Gruppe 01 und 04 |
| Direkter Bezug zum Bild an der Wand | Dritte (z. B. Veronese, Herzog von Modena) sind nicht im Bild und erst über Kommentare erreichbar |
| Verbindet unsere erste Idee mit dem Feed | |

**Möglicher Kompromiss:** Das Gemälde ist der fixierte (angepinnte) Post im Grid von Variante A.

---

## 6. Cast (Profile)

> Fakten stammen aus der Recherche auf dem Miro-Board. Punkte mit **(prüfen)** vor der Abgabe noch gegenchecken.

| Profil | Wer? | Rolle im Feed |
|---|---|---|
| **@zuanna.cuccina** | Zuanna Cuccina, geb. de Mutti, die Mutter im Bild | Stolz auf ihr Cochenille-Kleid, Mittelpunkt der Familie |
| **@antonio.cuccina** | Ehemann von Zuanna **(prüfen)** | Familienoberhaupt, Auftraggeber |
| **@alvise.cuccina** | Bruder **(prüfen)**, 1572 Taufpate von Veroneses Tochter | Bester Freund von Veronese |
| **@zuanne.cuccina** | Bruder **(prüfen)** | |
| **@girolamo.cuccina** | Kaufte 14 Jahre lang Grundstücke am Canal Grande für den Palast | Palast-Content, Immobilien-Flex |
| **@francesco.dimutti** | Zuannas Vater, hielt mit einem Partner das Importmonopol für Cochenille | Business-Account, Konkurrenz-Beef |
| **@paolo.veronese** | Der Maler, wohnte in derselben Pfarrei (San Felice) | Atelier-Posts, Behind the Scenes |
| **@inquisition_venezia** | Lud Veronese 1573 vor, weil sein „Abendmahl“ zu weltlich war; Veronese benannte es um in „Gastmahl im Hause des Levi“ | Der Hater im Netzwerk |
| **@antonio.maria.cuccina** | Sohn von Francesco, verkaufte den Zyklus an den Herzog von Modena für einen Adelstitel, starb 1644 | Bekommt erst nach dem Verkauf den blauen Haken |
| **@duca.di.modena** | Käufer des Cuccina-Zyklus | „Neu in meiner Sammlung 😍“ |
| **@august.iii** | Kaufte 1746 Gemälde aus Modena für Dresden **(prüfen)** | Letzter Besitzerwechsel |
| **@gemaeldegalerie.dresden** | Heute | Letzter Post: „Jetzt bei uns zu sehen“ |
| **@fides.official** / **@caritas.official** | Die Tugenden im Bild | Spaß-Accounts, kommentieren das Geschehen |
| **@la.balia** | Die Amme mit dem Baby Zuanne Battista | Blick „von unten“ auf die reiche Familie |

**Kinder** (aus dem Stammbaum auf dem Board): Girolamo, Andrea, Domenico, Francesco, Zuanne, Marc' Antonio, Zuanne Battista (Baby, bei der Amme), Marietta. Je nach Umfang einzelne Kinder als eigene Profile oder nur als Erwähnungen.

---

## 7. Beziehungsnetz (wer mag wen)

| Beziehung | Ton | Grundlage |
|---|---|---|
| Familie Cuccina ↔ Veronese | ❤️ herzlich, Lob | Fakt: gleiche Pfarrei, Altarbild 1562, Patenschaft 1572 |
| Veronese ↔ Inquisition | 🔥 beefy | Fakt: Verhör 1573 |
| Francesco di Mutti ↔ Konkurrenz im Farbhandel | 🔥 beefy | Plausible Fiktion (Monopol ist Fakt) |
| Ahnen ↔ Antonio Maria (Verkauf der Bilder) | 🔥 enttäuscht | Plausible Fiktion |
| Fides / Caritas ↔ alle | 😇 moralische Kommentare | Fiktion (Spaß-Accounts) |
| Veronese ↔ Fides | 😅 | Fakt: Veronese hat ihren Kopf beim Malen geändert |

---

## 8. Beispielinhalte

### @zuanna.cuccina ... Post „Das Kleid“ (Venedig, um 1571)

> **Caption:** Neues Kleid für das Familienbild 💃 Rot wie unser Geschäft. #cochenille #familybusiness

- **@francesco.dimutti:** Das ist MEIN Rot, Tochter ❤️ Importmonopol, Baby.
- **@paolo.veronese:** Ich hab noch nie so teures Rot gemalt. Und ich male für Könige.
- **@caritas.official:** Und spendest du davon auch was? 😇
- **@la.balia:** Schön ... ich trag seit drei Jahren dasselbe.
- **@antonio.cuccina:** Die schönste Frau Venedigs 😍

### @paolo.veronese ... Post „Planänderung“ (Venedig, um 1571)

> **Caption:** Kleine Planänderung beim Cuccina-Auftrag. Manchmal muss ein Kind weichen, damit die Komposition atmet. #behindthescenes #übermalt

- **@zuanna.cuccina:** Moment ... WELCHES Kind?? 😳
- **@fides.official:** Und mein Kopf war vorher auch schief, danke fürs Geraderücken 🙏
- **@alvise.cuccina:** Meister, du machst das schon ❤️
- **@inquisition_venezia:** Wir behalten deine Bilder im Auge.
- **@paolo.veronese:** @inquisition_venezia schon wieder ihr 🙄

### @antonio.maria.cuccina ... Post „Neuer Titel“

> **Caption:** Endlich adelig ✅ Ein paar alte Bilder gegen einen Titel, fairer Deal. #upgrade

- **@duca.di.modena:** Danke für die Bilder, schmücken jetzt meinen Palast 😌
- **@girolamo.cuccina:** 14 Jahre Grundstücke gekauft. Und DU verkaufst die Bilder?!
- **@zuanna.cuccina:** Ich bin sprachlos. Mein Kleid hängt jetzt in Modena.
- **@paolo.veronese:** Wenigstens werden sie noch angeschaut.
- **@gemaeldegalerie.dresden:** Wir sehen uns 1746 😉 **(prüfen)**

### Alltags-Post (Beispiel)

> **@zuanna.cuccina:** Gestern Abend: Kalbsbraten, Weißbrot und ein guter Wein 🍷 Die Amme kriegt die Reste.
> **@la.balia:** Danke, wie immer.

---

## 9. UI- und Designelemente

- **Instagram-Muster:** Grid, Post-Ansicht, Herzen, Kommentare, Profilkopf mit Bio, Follower, Story-Highlights
- **Follower-Zahlen als Statussymbol:** reich = viele Follower
- **Verifizierter Haken:** Antonio Maria bekommt ihn erst nach dem Kauf des Adelstitels
- **Story-Highlights pro Profil:** z. B. „Palazzo“, „Cochenille-Business“, „Unser Bild“
- **Datums- und Ortszeile:** an jedem Post („Venedig, 1571“)
- **Zoom-Animation:** vom Grid in den Post
- **Visueller Stil:** modernes Instagram-Interface, kombiniert mit Bildausschnitten und Farben aus dem Gemälde (Cochenille-Rot, Ultramarin)
- **Bedienung:** Touchscreen im Museum, große Touch-Flächen, Home-Button immer sichtbar, Auto-Reset nach Inaktivität

---

## 10. Fakten und Fiktion

Der Feed mischt belegte Fakten mit erfundenem Alltag und Dialog. Das sollte für Besucher erkennbar bleiben:

- **Fakten** (z. B. Cochenille-Monopol, Patenschaft 1572, Inquisition 1573, Verkauf an Modena) stehen in Captions und tragen Jahr und Ort.
- **Fiktion** (Alltag, Tonfall, Streit) ist bewusst überzeichnet.
- **Idee:** ein kleines „📜 Fakt“-Badge an Posts mit belegtem Inhalt. Ein Tap öffnet eine kurze Quelle oder Erklärung.

---

## 11. Umfang für den Prototyp (bis Montag)

Vollständig: 8 Profile × 5 Posts × 5 Kommentare = **200 Kommentare**. Für den Prototyp reduziert:

- **3 bis 4 Profile komplett** (Vorschlag: @zuanna.cuccina, @paolo.veronese, @antonio.maria.cuccina, @francesco.dimutti)
- Übrige Profile mit Profilkopf und 1 bis 2 Posts, Rest als Platzhalter
- **Screens:** Startscreen Grid (Variante A), Startscreen Gemälde (Variante B), Post-Ansicht, Profil-Ansicht
- **Klickpfad:** Grid → Post → @Name → Profil → Post zum Vorführen

---

## 12. Offene Fragen

- Figma-Prototyp oder Wireframes in Miro?
- Welche Fakten mit **(prüfen)** müssen wir noch absichern?
- Wie viel Fiktion ist für den Kurs in Ordnung?
- Dürfen Bildausschnitte des Gemäldes als Post-Bilder verwendet werden (Rechte der Gemäldegalerie)?
- Wie lang soll eine durchschnittliche Nutzung dauern (Ziel z. B. 3 bis 5 Minuten)?
