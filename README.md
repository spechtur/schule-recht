# 🚦 Ampel-Check: Schule und Recht

Eine interaktive Slide-Präsentation mit 12 Fällen aus dem Schulalltag, die rechtlich eingeordnet werden müssen. Konzipiert als aktivierende Abschlussübung für Weiterbildungen und Studiengänge im Bereich Schulrecht.

## Idee

Die Teilnehmenden sehen auf dem Bildschirm jeweils eine kurze Fallbeschreibung aus dem Schulalltag und müssen diese mit farbigen Karten einordnen:

- 🟢 **Grün** – Unbedenklich
- 🟠 **Orange** – Heikel, kommt drauf an
- 🔴 **Rot** – No-Go

Anschliessend wird die Einordnung mit einer kurzen rechtlichen Begründung eingeblendet. Das Format eignet sich besonders gut als «Outro» nach einem Input-Block – es nimmt die Inhalte nochmals auf, aktiviert die Gruppe und macht Graubereiche sichtbar.

## Themenfelder der 12 Fälle

- Datenschutz (E-Mail, Noten, Fotos, KI-Tools)
- Sorgfalts- und Aufsichtspflicht (Schulreise, Wandertag, Pausenplatz)
- Recht am eigenen Bild (Social Media)
- Persönlichkeitsrechte (Handy, Privatsphäre)
- Religionsfreiheit vs. Schulpflicht (Schwimmunterricht)
- Medikamentenabgabe
- Elternrechte (Klassenlager)

## Bedienung

| Aktion | Eingabe |
|---|---|
| Nächste Folie | `→` Pfeiltaste, `Leertaste` oder Button «Weiter» |
| Vorherige Folie | `←` Pfeiltaste oder Button «Zurück» |
| Touchscreen | Wischen nach links / rechts |

Für die Präsentation im Plenum empfiehlt sich der Vollbildmodus (`F11`).

## Technisch

Reines HTML/CSS/JS in einer einzigen Datei – keine Abhängigkeiten, kein Build-Schritt. Einfach `ampel_check.html` im Browser öffnen. Die Textgrössen skalieren dynamisch mit der Bildschirmgrösse (Viewport-basiert via `clamp()`), sodass die Präsentation auf Laptop, Beamer und Tablet gleichermassen funktioniert.

## Einsatzkontext

Entwickelt für den **Master SEK I** an der Pädagogischen Hochschule Graubünden (PHGR), Modul «Schule und Recht». Kann frei für andere Weiterbildungskontexte adaptiert werden.

## Hinweis

Die rechtlichen Einordnungen dienen als Diskussionsgrundlage und Orientierung. Je nach Kanton, Gemeinde und konkretem Sachverhalt können sich Nuancen ergeben. Im Zweifelsfall gilt: nachfragen, dokumentieren, Schulleitung einbeziehen.

## Lizenz

Frei verwendbar für Bildungszwecke. Erstellt mit Unterstützung von [Claude](https://claude.ai) (Anthropic).
