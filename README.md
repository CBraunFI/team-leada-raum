# Team-Leada · Raum-Modus

Konzept-Prototyp: Leada steht als Gerät in der Tischmitte eines Team-Treffens.
Wer teilnimmt, **meldet sich mit dem eigenen Leada-Konto an** (Handy an den Sockel).
Erst dann kennt Leada Rolle, Verantwortung, Aufgaben und Stärken dieser Person, und zwar
nur das, was sie für das Team freigegeben hat. Persönliches Coaching bleibt außen vor.

Leada moderiert, beantwortet Rückfragen, hält auf dem Zusammenarbeit-Board nur fest,
was bestätigt ist, und vertritt Abwesende mit dem, was diese freigegeben haben.
Ein Stummschalter am Sockel trennt das Mikrofon.

**Live:** https://cbraunfi.github.io/team-leada-raum/

## Szenarien

| Link | Szenario | Worum es geht |
|---|---|---|
| `#weekly` | Team-Weekly | Anna fehlt, Leada vertritt sie mit Annas Freigabe; Stummschalter-Moment |
| `#rollen` | Wer übernimmt was? | Rückfragen an Leada, Vorschlag aus den Team-Profilen, „Woher weißt du das?“ |
| `#konflikt` | Zwei Prioritäten | Kunde gegen Release: erst fragen, Verantwortungen zeigen, die Teamleitung entscheidet |
| `#retro` | Retro nach dem Release | Beobachtungen mit Belegen, Grenze bei persönlichem Feedback |

## Zustände des Geräts

| Zustand | Was man sieht |
|---|---|
| Anmeldung | goldener Strom von der Person zum Sockel, ✓ am Namensschild |
| Ruhe | Kern atmet langsam, Ring gedimmt |
| Zuhören | Lichtbogen wendet sich der sprechenden Person zu, Worte fließen als Punkte zu Leada |
| Denken | Bogen kreist, Blick leicht nach oben |
| Sprechen | goldener Wellenzug unter den Augen, Blick auf die angesprochene Person |
| Stumm | Licht aus, Augen zu, Hinweis in Koralle |

## Technik

Eine einzige `index.html`, Three.js 0.160 vom CDN (jsDelivr), kein Build.
HD-Modus: 1,5-faches Supersampling (bis ca. 4K-Pixel), 4×-MSAA in der Nachbearbeitung, 4096er-Schatten.
Lokal starten: `python -m http.server` im Ordner und `http://localhost:8000` öffnen.
Alle Personen und Inhalte sind erfunden.
