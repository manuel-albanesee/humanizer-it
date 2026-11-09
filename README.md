# humanizer-it

Skill per Claude Code che riscrive testi in italiano dal suono "generato da AI" così che sembrino scritti dall'autore, senza cambiarne il contenuto.

Riconosce e corregge 36 schemi tipici della scrittura dei modelli linguistici, dai più forti ai più deboli: contrasti "non è solo X, è Y", chiuse a effetto, aperture epiche, domande retoriche con risposta, triadi e coppie di sinonimi, connettivi a ogni frase, gerundi a catena, stile nominale, lineette, rafforzativi, linguaggio da brochure, grassetti decorativi, il paragrafo "In conclusione". Include segnali specifici dell'italiano (calchi dall'inglese, registro tu/Lei incoerente) e segnali legati al genere (post social, narrativa).

## Installazione

Clona il repo nella directory delle skill di Claude Code:

```bash
git clone https://github.com/manuel-albanesee/humanizer-it.git ~/.claude/skills/humanizer-it
```

## Uso

```
/humanizer-it <testo da riscrivere>
```

Oppure chiedi a Claude di "umanizzare", "rendere meno AI" o "rendere più naturale" un testo italiano. Se indichi un file, la skill riscrive solo la prosa e lascia invariati codice, comandi, percorsi e metadati.

## File

- `SKILL.md`: istruzioni della skill e catalogo degli schemi con esempi prima/dopo.
- `references/fonti.md`: studi e fonti su cui si basano gli schemi.

## Licenza

MIT. Vedi [LICENSE](LICENSE) e [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
