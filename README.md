
Building AI course project

# Blind-Learning-AI-Inklusive-Onlinekurse-intelligent-anpassenProjektname
Blind Learning AI – Inklusive Onlinekurse intelligent anpassen


Blind Learning AI ist ein KI-gestütztes System, das Onlinekurse automatisch auf die Bedürfnisse blinder und sehbehinderter Menschen anpasst. Es nutzt Künstliche Intelligenz, um Lerninhalte barrierefrei umzuwandeln – z. B. durch das automatisierte Einfügen von Alternativtexten, Tastenkombinationen, Tastatur-Navigation, strukturierter Audiobeschreibung und die Bereitstellung von Übungshilfen im Screenreader-kompatiblen Format.

Hintergrund
Das Problem:
Obwohl digitale Bildung boomt, bleiben viele blinde und sehbehinderte Menschen von modernen Onlinekursen ausgeschlossen. Die Gründe:
•	Fehlende Screenreader-Kompatibilität
•	Keine Tastaturnavigation
•	Bilder/Videos ohne Audiobeschreibung oder Alternativtexte
•	Fehlende Strukturierung (z. B. durch Überschriftenebenen)
•	Unzureichende Hilfestellungen in Prüfungen oder Übungen
Relevanz:
Laut WHO leben weltweit mindestens 43 Millionen blinde und über 250 Millionen stark sehbehinderte Menschen. In Deutschland betrifft es über eine halbe Million. Inklusive Bildung ist ein Menschenrecht (UN-BRK Artikel 24), aber in der Praxis schwer umsetzbar.
Persönliche Motivation:
Ich bin selbst stark sehbehindert und habe erlebt, wie frustrierend es ist, wenn man an technischen Barrieren scheitert – obwohl man die Inhalte kognitiv problemlos bewältigen könnte. Dieses Projekt soll echten Zugang schaffen.
________________________________________
Daten und KI-Techniken
Datenquellen:
•	Offene Onlinekursplattformen (z. B. Moodle-Kurse, Open Educational Resources)
•	KI-trainierte Modelle zu Sprache (z. B. Whisper, GPT, TTS-Systeme)
•	OpenStreetMap für Navigationseinbindung
•	Barrierefreiheits-Richtlinien (WCAG, BITV 2.0)
Mögliche KI-Techniken:
•	NLP: Struktur-Analyse von Texten, automatische Gliederung
•	Bildanalyse: Objekterkennung und Bildbeschreibung (z. B. mithilfe von CLIP)
•	Sprachtechnologien: Audiobeschreibung, Text-to-Speech (TTS)
•	Recommender Systems: Adaptive Lernwege vorschlagen
•	Automatische Prüfungsanpassung: Fragen vereinfachen, Alternativen bieten
•	Barrierefreiheits-Prüfmodul: KI prüft, ob Inhalte barrierefrei sind, und gibt Feedback
Optional: Technischer Prototyp (später möglich)
Eine Weboberfläche, in die ein Kurs im PDF- oder HTML-Format hochgeladen wird. Die KI analysiert, überarbeitet und gibt eine barrierefreie Version zurück.

Wie wird es verwendet?
Zielgruppe:
•	Blinde und sehbehinderte Menschen aller Altersgruppen
•	Lehrkräfte, Behörden, Bildungseinrichtungen, Inklusionsbeauftragte
•	Entwickler:innen von Lernplattformen
Anwendungsszenario:
1.	Dozent lädt Kursunterlagen auf der Plattform hoch
2.	Die KI prüft Struktur, Bilder, Navigation
3.	Inhalte werden automatisch überarbeitet:
o	Alternativtexte
o	Tastenkombinationen ergänzt
o	Navigationshilfe erstellt
o	Struktur- und Inhaltsprüfung
4.	Barrierefreie Version wird zum Download angeboten
5.	Optionale Audioführung wird als MP3 generiert
________________________________________
Herausforderungen
•	Vielfalt der Plattformen: Moodle, edX, Udemy – jede ist technisch anders aufgebaut
•	Subjektivität bei Beschreibung: Nicht jede KI-Bildbeschreibung ist sinnvoll für blinde Menschen
•	Datenschutz: Prüfungen und Materialien müssen anonym verarbeitet werden
•	Keine Lösung für alle Behinderungsformen – Projekt fokussiert auf Sehbehinderung

Wie geht es weiter?
Vision:
Ein Open-Source-Werkzeug, das in jede Lernplattform eingebunden werden kann. Die Community kann eigene Bausteine ergänzen – z. B. neue Sprachen, weitere Screenreader, spezielle Anforderungen (z. B. Gebärdensprachunterstützung).
Ausbaustufen:
•	Integration mit ChatGPT-API als Lernassistent für Fragen
•	Partnerprogramme mit Volkshochschulen und Blindenverbänden
•	Teilnahme an barrierefreien Hackathons
•	Erstellung von Open Datasets mit barrierefreien Kursinhalten
________________________________________
Danksagung
Dieses Projekt wurde inspiriert von:
•	Der UN-Behindertenrechtskonvention
•	Projekten wie Be My Eyes, Seeing AI
•	Der AI Idea Gallery und der OpenAI-Community
•	Open-Source-Kollektiven wie Hugging Face, Mozilla TTS
•	Persönlicher Austausch mit blinden Kursteilnehmenden aus dem BFWRosenheim

