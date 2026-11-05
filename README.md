# LilyLingua – Übersetzungen

Alle Übersetzungen von [lilylingua.de](https://lilylingua.de): Arbeitsblätter, die Videoserie
„Deutsch im Alltag“, die Reiseserie und Mathe (Klassen 1–13), in bis zu 38 Sprachen.
Die Texte sind gemeinfrei (CC0), und jede und jeder kann sie verbessern.

*English below.*

## Was ist drin?

| Ordner | Inhalt |
|---|---|
| `worksheets/<lernsprache>/<blatt>/` | `source.json` = Original, `<sprache>.json` = Übersetzung |
| `series/deutsch-im-alltag/<folge>/` | Kernsätze und Untertitel je Sprache, `de.json` = Original |
| `series/reise/<folge>/` | dasselbe für die Reiseserie |
| `math/ui/` | alle Mathe-Texte der Website, `en.json` = Original |
| `math/learning-areas/<lernsprache>/` | Textaufgaben für /english, /espanol, /polski, /ukrainska |
| `languages.json` | Sprachkürzel der Website und ihr BCP-47-Code (z. B. `ge` = `ka` Georgisch) |
| `PROVENANCE.md` | Übersicht: wer oder welches KI-Modell welche Sprache übersetzt hat |

## Herkunft: Mensch oder KI?

Jede Datei sagt unter `_meta`, woher ihr Text stammt:

```json
"_meta": {
  "language": "fr",
  "source": "de",
  "provenance": { "type": "ai", "models": ["Anthropic Claude Opus 5.5"] },
  "review": "unreviewed"
}
```

- `provenance.type`: `original`, `ai`, `human` oder `mixed` (KI-Entwurf, von Menschen überarbeitet)
- `provenance.models`: **bei KI immer das genaue Modell** (z. B. „Anthropic Claude Opus 5.5“, „OpenAI gpt-4.1“)
- `provenance.contributors`: bei Menschen der GitHub-Name
- `review`: `unreviewed`, `ai-reviewed` oder `native-reviewed`

Die meisten Texte sind bisher KI-Übersetzungen, die noch kein Muttersprachler gegengelesen hat.
Genau dabei hilft die Community am meisten.

## Mitmachen

Siehe [CONTRIBUTING.md](CONTRIBUTING.md). Kurz: Datei ändern, `_meta` anpassen, Pull Request stellen.
Jeder Beitrag wird vor der Übernahme automatisch und von Hand geprüft.

## Lizenz und Marke

- Übersetzungen und Texte: [CC0 1.0](LICENSE), also gemeinfrei: nutzen, ändern, verkaufen, ohne Pflicht zur Nennung.
  Wir freuen uns trotzdem über „Quelle: LilyLingua (lilylingua.de)“.
- Name und Logo „LilyLingua“ sind **nicht** Teil der freien Lizenz, siehe [TRADEMARK.md](TRADEMARK.md).

---

## English

All translations used on [lilylingua.de](https://lilylingua.de) (worksheets, the video series
“Deutsch im Alltag”, the travel series and maths for grades 1–13) in up to 38 languages, dedicated to the public domain under CC0 1.0.

Every file states its origin in `_meta.provenance`. Machine translations always name the exact model.
Most texts have not been reviewed by native speakers yet, and that is where your help matters most.
See [CONTRIBUTING.md](CONTRIBUTING.md). The name and logo “LilyLingua” are not covered by the open licence
(see [TRADEMARK.md](TRADEMARK.md)).
