# Mitmachen / Contributing

Danke, dass du hilfst! Jede Korrektur macht die Arbeitsblätter und Videos für Lernende besser.

## So geht's

1. Datei suchen, z. B. `worksheets/de/baecker-und-cafe/fr.json`.
2. Nur die Texte ändern, **nicht** die Schlüssel, IDs, Zeiten (`start`/`end`) oder Platzhalter wie `{name}` und `{a}`.
3. `_meta` anpassen:
   - Selbst korrigiert → `provenance.type` auf `mixed` (oder `human`, wenn du alles neu geschrieben hast),
     deinen GitHub-Namen in `provenance.contributors` eintragen.
   - Als Muttersprachler gegengelesen → `review` auf `native-reviewed`.
   - **KI benutzt?** Dann das genaue Modell in `provenance.models` eintragen (z. B. „DeepL“, „OpenAI gpt-4.1“).
     Das ist Pflicht, damit Lernende wissen, was sie vor sich haben.
4. Pull Request stellen und kurz schreiben, was du geändert hast.

## Regeln

- Kein HTML, keine Links, keine Werbung. Solche Beiträge werden automatisch abgelehnt.
- Bei Wörtern, die Lernende auf Deutsch schreiben sollen (Lücken, Artikel), bleibt die deutsche Lösung erhalten.
- Absichtlich falsche Antwortmöglichkeiten in den Videos (A/B/C) sollen auch in der Übersetzung erkennbar falsch bleiben.
- Anrede: überall „du“ bzw. die vertraute Form (Ausnahme Urdu: höfliches „آپ“).
- Alkohol und Rauchen stehen in der 3. Person („Er trinkt Wein“), nie in der Ich-Form.

## Was passiert dann?

Jeder Beitrag wird geprüft (automatisch und von Hand) und landet danach auf lilylingua.de.
Mit deinem Beitrag stellst du ihn unter CC0 1.0 (gemeinfrei): Jeder darf ihn frei nutzen, auch LilyLingua
in Website, Büchern und Videos. Deinen GitHub-Namen in `_meta.provenance.contributors` nennen wir trotzdem gern.

---

**English:** Edit only the text values, keep keys/IDs/timings/placeholders, update `_meta`
(add yourself to `provenance.contributors`, set `review` to `native-reviewed` if you are a native speaker,
and always name the exact model if you used machine translation), then open a pull request. Contributions are dedicated to the public domain under CC0 1.0.
