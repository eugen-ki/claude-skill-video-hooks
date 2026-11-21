---
name: video-hooks
description: Use when the member needs the opening seconds of a video (Hook, Einstieg, erste Sätze, Intro-Ideen) for YouTube, Reels, TikTok or Shorts, wants several hook options to test, or says an existing hook feels flat, boring or gets swiped away.
---

# Video-Hooks

Schreibt Hooks für **ein** Video und bewertet sie. Die besten drei kommen als Paket aus Bild, gesprochenem Satz und Texteinblendung, die alle auf dieselbe Idee zeigen.

Grundsatz: Ein Hook hat genau eine Aufgabe. Der richtige Zuschauer soll sofort wissen, worum es geht, und eine offene Frage im Kopf haben.

## Schritt 1: Eingaben

Lies `~/.claude/mein-profil.md` (Zielgruppe, deren Worte, Stimme, Belege). Fehlt sie, frag kurz nach der Zielgruppe oder biete **mein-profil** an.

Brauchst du: Thema oder Gliederung, und die Plattform (YouTube lang oder Kurzvideo). Hat das Mitglied keine überraschende Tatsache genannt, frag genau eine Sache:
"Was ist das Überraschendste in diesem Video, das deine Zuschauer vermutlich noch nicht wissen?"
Diese Antwort ist der Rohstoff für den Hook. Kommt keine Antwort, arbeite mit einer naheliegenden Annahme und schreib sie oben in die Datei: `Annahme: ...`.

| Plattform | Bild | Gesprochener Hook | Texteinblendung |
|---|---|---|---|
| Reel, TikTok, Short | erste 1 bis 2 Sekunden | 1 bis 2 Sätze, unter 5 Sekunden (etwa 12 Wörter) | höchstens 6 Wörter |
| YouTube lang | erste 3 Sekunden | 1 bis 3 Sätze, unter 15 Sekunden (etwa 35 Wörter) | Titel oder Kurzform davon |

## Schritt 2: Den Wunsch finden

Ordne das Video einem Grundwunsch zu: **Geld, Zeit, Ruhe** (weniger Stress, Gesundheit) oder **Ansehen** (klug wirken, vorne sein).

Versprich den Wunsch nicht als allgemeine Floskel ("spar Zeit", "verdien mehr"), das klingt nach Werbung. Versprich einen **Schritt daneben**: ein konkretes Bild davon, wie es sich anfühlt, wenn der Wunsch erfüllt ist.
Eine echte, messbare Angabe aus dem Video ("5 Minuten statt einer Stunde") ist keine Floskel. Sie darf in den Hook, am besten als Kontrast oder in der Texteinblendung. Mindestens einer der Top 3 nutzt den Schritt daneben.

| Wunsch | Direkt (wirkt unglaubwürdig) | Ein Schritt daneben |
|---|---|---|
| Geld | "Verdien mehr Geld" | "Lass die Arbeit, die du hasst, von allein laufen" |
| Zeit | "Spar 10 Stunden pro Woche" | "Fang nie wieder mit einer leeren Seite an" |
| Ansehen | "Werde Experte" | "Bau, wofür andere ein ganzes Team brauchen" |
| Ruhe | "Weniger Stress im Job" | "Hör auf, Dinge per Hand zu machen, die ein Werkzeug in Sekunden erledigt" |

## Schritt 3: Fünf Blickwinkel, je mindestens ein Hook

1. **Ich habe:** "Ich habe gerade [X] mit [Y] geschafft."
2. **Wenn ich:** "Wenn ich heute [X] wollte, würde ich [Y]."
3. **Du:** "Wenn du [X] willst, nimm [Y]."
4. **Frage:** "Geht [X] in unter [Y]?"
5. **Jemand anders:** "[Person] hat [X] in [Y] geschafft." Nur mit echter Person und echtem Ergebnis. Gibt es keine, lass diesen Blickwinkel weg und schreib "entfällt, kein echtes Beispiel".

Die Top 3 sollen aus verschiedenen Blickwinkeln kommen. Die Liste "Alle fünf Blickwinkel" in der Ausgabe enthält nur die Hooks, die nicht in den Top 3 stehen.

## Schritt 4: Die stärksten 2 bis 3 in passende Formen bringen

Wähle nur Formen, die zum Inhalt passen: Geheimnis lüften, Fallbeispiel, Vergleich vorher/nachher, Frage, Anleitung, Liste, Gegenthese, eigene Geschichte, Problem zuspitzen.
Eine Gegenthese ("X ist falsch") braucht sofort einen Beleg, sonst wirkt sie hohl.

## Schritt 5: Bausteine prüfen

Jeder Hook bekommt eine Zeile, welche Bausteine drin sind:
**Wer** (ich, du, eine Person), **Tat** (gebaut, ersetzt, entdeckt), **Ergebnis**, **Kontrast** (vorher/nachher, 0 auf X, per Hand vs. automatisch), optional **Beleg** ("nach 30 Tests") und **Zeit** ("an einem Wochenende").
Mindestens Wer, Tat, Ergebnis und Kontrast. Beleg und Zeit nur mit echten Angaben, sonst `[Klammer]`. Ein Baustein in `[Klammern]` zählt als fehlend. Jedes Wort zählt nur für einen Baustein. Die Zahl am Ende ist die Anzahl vorhandener Bausteine von 6.

## Schritt 6: Top 3 als Paket und vier Prüfungen

Für jeden der besten drei:
- **Bild:** was in den ersten Sekunden zu sehen ist (Bewegung, Ergebnis, etwas Unerwartetes).
- **Gesprochen:** der Satz, so einfach, dass ein Zwölfjähriger ihn versteht.
- **Text:** ergänzt den gesprochenen Satz, wiederholt ihn nicht.

Prüfungen, jeweils ja oder nein:
1. **Passt zusammen:** Bild, Wort und Text zeigen auf dieselbe Idee.
2. **Sofort zur Sache:** das Thema steht in den ersten 5 Wörtern. Keine Begrüßung, kein "Heute zeige ich euch".
3. **Klar:** ein Fremder versteht beim ersten Hören, worum es geht. Keine Fachwörter, kein doppeldeutiges Wortspiel.
4. **Neugier:** eine Frage ist offen, die das Video beantwortet.

Empfiehl nur Hooks mit vier mal ja. Sonst schreib die Korrektur dazu.

## Ausgabe

Speichere `hooks-<thema>.md` im aktuellen Ordner (Thema in höchstens 5 kleinen Wörtern mit Bindestrichen, ä als ae, ö als oe, ü als ue, ß als ss) und zeig sie im Chat:

```
## Wunsch
Grundwunsch: [..] | Ein Schritt daneben: [..]

## Top 3
### Hook 1 ([Form], [Blickwinkel])
Gesprochen: "[..]"
Bild: [..]
Text: "[..]"
Bausteine: Wer, Tat, Ergebnis, Kontrast, Zeit (5 von 6)
Prüfungen: 4 von 4

## Alle fünf Blickwinkel
1. Ich habe: ..
...

## Empfehlung
[Welcher Hook und warum, direkt und mit Meinung]
```

Nutzt das Mitglied danach **youtube-skript**, wird der empfohlene Hook der erste Satz des Intros.

## Regeln

- Neugier ja, Köder nein. Der Hook verspricht nur, was das Video liefert.
- Verlust zieht stärker als Gewinn: "Du verschenkst jede Woche 5 Stunden" schlägt "Spar 5 Stunden". Nur wenn es stimmt.
- Ein Hook pro Video. Nicht drei Ideen in den Einstieg packen.
- Nie Ergebnisse, Zahlen oder Personen erfinden.
- Kurze deutsche Wörter. Lange Hauptwörter ("Prozessoptimierung") ersetzen ("schneller fertig").
