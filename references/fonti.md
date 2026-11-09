# Fonti degli schemi

Questo file serve a chi vuole verificare o aggiornare la skill. Non serve leggerlo per applicarla.

Legenda: **[PR]** pubblicazione sottoposta a revisione tra pari (rivista o atti di convegno); **[ACC]** rivista o sede accademica; **[PRE]** preprint non ancora revisionato; **[DIV]** divulgazione o pratica professionale. I numeri tra parentesi quadre indicano gli schemi di SKILL.md che la fonte sostiene.

## Studi sull'italiano

- **[PR] "AI detection in Italian essays through different text representations and adversarial robustness evaluation"**, *Scientific Reports* (2026). https://www.nature.com/articles/s41598-026-51613-9
  Corpus di 1000 temi: 500 di studenti universitari italiani e 500 di ChatGPT (GPT-3.5) sugli stessi titoli. Rispetto agli studenti, i testi generati hanno frasi in media più corte, più parole lunghe, meno avverbi e pronomi. La parola "conclusione" compare in quasi tutti i testi generati ed è tra i tratti più utili ai classificatori; aggiungere "perché", "si" e "non" rende i testi più "umani"; ridurre il numero di frasi li rende più discorsivi, "tipici della scrittura umana (e probabilmente ancor più in italiano)". Gli autori notano anche la scarsa capacità di GPT di costruire subordinate e segnali di coesione, e che i testi umani vengono scambiati per AI più spesso del contrario. [§12, §31, Quando non intervenire]

- **[ACC] Giuseppe Antonelli, "Storia brevissima (ma molto intensa) dell'IA-taliano"**, *Lingue e Culture dei Media* 9/1 (2025). https://riviste.unimi.it/index.php/LCdM/article/view/29341
  Test ripetuti tra novembre 2023 e giugno 2025 su ChatGPT, Copilot, Gemini e Claude. Osserva: allocutivo tu sempre di default; coppie di parole legate da "e" / "o"; testi costruiti intorno a poche parole chiave ripetute (corretto, importante, comunicazione); riformulazione degli elementi chiave della domanda in apertura; considerazioni moralistiche finali; tecnicismi infilati e talvolta usati a sproposito quando si chiede un registro specialistico; nei post "giovanili" emoji quasi a ogni riga, almeno cinque hashtag con almeno uno in inglese, lessico tarato troppo in alto, finto parlato (NOOOO, "muoio dentro"); in narrativa ripetizioni circolari della parola-tema e strutture correlative simmetriche. [§8, §10, §31, §32, §34, §35, §36]

- **[ACC] "Sui testi generati dall'intelligenza artificiale. Verso un nuovo rapporto tra norma e uso?"**, tema del mese dell'Accademia della Crusca (2026). https://accademiadellacrusca.it/it/contenuti/sui-testi-generati-dallintelligenza-artificiale-verso-un-nuovo-rapporto-tra-norma-e-uso/46422
  Riprende Antonelli (2026) sul "generoso ricorso a connettivi di raccordo tra le frasi", De Cesare (2026) sulle "impronte algoritmiche dell'inglese" (calchi e interferenze) e Palermo (2026) sulla diffusione del gerundio irrelato nei testi generati (esempio di Gemini sugli Shardana). Segnala anche le incoerenze fisiche nelle descrizioni narrative (il lume che proietta la propria ombra) e avverte che i testi generati non si riconoscono a prima vista. [§9, §19, §33, §36]

- **[ACC] Studio sulle favole generate da LLM**, *Linguistica e Filologia* (Università di Bergamo). https://hdl.handle.net/10446/331167. Sintesi divulgativa: "ChatGPT, bias algoritmici e rischi per la diversità linguistica II", *Linguisticamente*. https://www.linguisticamente.org/chatgpt-bias-algoritmici-e-rischi-per-la-diversita-linguistica-ii/
  Favole di GPT-3.5 Turbo, GPT-4o-mini, Minerva-7B e Teuken-7B contro favole umane. Il rapporto tipi/occorrenze degli aggettivi è 6,95% nelle favole generate contro 21,70% nelle umane; le interiezioni umane sono più di tre volte quelle generate; a temperatura 0 prompt identici danno incipit identici ("C'era una volta, in un piccolo villaggio ai piedi di una grande montagna..."). [§36, Appiattimento]

- **[PR] Anna-Maria De Cesare (2023), "Assessing the quality of ChatGPT's generated output in light of human-written texts. A corpus study based on textual parameters"**, *CHIMERA* 10, pp. 179–210. Studio di corpus sui parametri testuali. [contesto]

- **[ACC] Mirko Tavosanis (2024), "Valutare la qualità dei testi generati in lingua italiana"**, *AI-Linguistica* 1(1). https://doi.org/10.62408/ai-ling.v1i1.14
  Testi di ChatGPT-3.5 e 4 vicini alle produzioni professionali umane, con alcuni punti di divergenza. [contesto]

- **[ACC] Francesco Cicero, "L'italiano delle intelligenze artificiali generative"**, *Italiano LinguaDue* (Università di Milano). Analisi dei testi informativi di ChatGPT, Bard e Bing Chat. [contesto]

- **[PR] DeSegMa-IT at EVALITA 2026: "Detection and Segmentation of Machine Generated Texts in Italian"** (Puccetti et al.). https://aclanthology.org/2026.evalita-1.5/
  Primo shared task italiano sul rilevamento e la segmentazione di testo generato. Conferma che il rilevamento in italiano è un problema aperto. [Quando non intervenire]

- **[PR] "AI vs. Human: Effectiveness of LLMs in Simplifying Italian Administrative Documents"**, CLiC-it 2024. https://ceur-ws.org/Vol-3878/91_main_long.pdf
  Nella semplificazione di testi amministrativi gli LLM cambiano il testo più delle persone, sia nella struttura sia nel lessico. [contesto]

- **Progetto DFG "Generate-IT. LLM-Generated Texts in Italian: A Linguistic Study"** (TU Dresda, dal 2025, A.-M. De Cesare). https://gepris.dfg.de/gepris/projekt/550431710
  Progetto in corso sui tratti "simili all'inglese" e sull'eventuale impoverimento dell'italiano generato. Da controllare per pubblicazioni future.

## Studi su più lingue o sull'inglese

- **[PRE] "Artificial Epanorthosis: Why large language models overuse a classical rhetorical figure, and how to mitigate it"**, arXiv 2607.21498 (2026). https://arxiv.org/abs/2607.21498
  Misura la famiglia "non X, ma Y" per genere. Gli LLM ne abusano nei testi oratori e persuasivi (circa il doppio della frequenza umana, vicino al triplo in italiano) e la usano meno delle persone nelle domande e risposte informali; nell'argomentazione, nel giornalismo e nella prosa enciclopedica sono in linea. Tre o più contrasti in un passaggio breve sono un indizio forte ma mai conclusivo; la correzione autentica ("o meglio") è legittima. In italiano un'istruzione di una riga dimezza il fenomeno. Divulgazione italiana: Jackalope.it, AITalk; *Il Post*, "Perché i chatbot sono fissati con: 'Non è X, è Y'?" (luglio 2026). [§1]

- **[PR] Reinhart et al. (2025), "Do LLMs write like humans? Variation in grammatical and rhetorical styles"**, *PNAS* 122(8), e2422455122. https://doi.org/10.1073/pnas.2422455122
  Gli LLM con instruction tuning usano proposizioni participiali da 2 a 5 volte più delle persone (GPT-4o 5,3 volte) e nominalizzazioni 1,5–2 volte di più; alcune parole (tapestry, intricate, palpable, camaraderie) compaiono oltre 100 volte più spesso. Lo stile resta denso e nominale anche quando si chiede narrativa. [§15, §19, §20]

- **[PR] Kobak et al. (2025), "Delving into LLM-assisted writing in biomedical publications through excess vocabulary"**, *Science Advances* 11(27), eadt3813. https://doi.org/10.1126/sciadv.adt3813
  Su oltre 15 milioni di abstract PubMed, dopo ChatGPT aumentano di colpo parole di stile (verbi e aggettivi come delves, showcasing, underscores, crucial), non di contenuto. [§15]

- **[PR] Juzek & Ward (2025), "Why Does ChatGPT 'Delve' So Much? Exploring the Sources of Lexical Overrepresentation in Large Language Models"**, COLING 2025. https://aclanthology.org/2025.coling-main.426/
  L'eccesso lessicale sembra dovuto soprattutto all'addestramento con feedback umano (RLHF), non ai dati o all'architettura. [§15]

- **[PR] Muñoz-Ortiz, Gómez-Rodríguez, Vilares (2024), "Contrasting Linguistic Patterns in Human and LLM-Generated News Text"**, *Artificial Intelligence Review* 57, 265. https://doi.org/10.1007/s10462-024-10903-2
  I testi umani hanno una distribuzione della lunghezza delle frasi più dispersa e un vocabolario più vario. [§12]

## Pratica e divulgazione

- **[DIV] stop-slop-it** (licenza MIT), https://github.com/dascanfe/stop-slop-it. Liste di frasi di riempimento, aperture epiche, gergo aziendale, avverbi rafforzativi, domande retoriche, oggetti che agiscono come persone, nominalizzazioni, esempi di microcopy e post. [§2, §4, §5, §16, §20, §21, §35]
- **[DIV] *Il Post*, "Si può riconoscere un testo scritto dall'intelligenza artificiale?"** (marzo 2026). https://www.ilpost.it/2026/03/30/scoprire-chi-scrive-con-chatgpt/. Connettivi abbondanti, enfasi ("epocale, clamoroso"), "un monumento a", "una testimonianza di", ripetizione di frasi identiche a breve distanza, emoji nel 70% dei messaggi di ChatGPT secondo uno studio citato, inaffidabilità dei rilevatori. [§9, §15, §16, §35]
- **[DIV] Register.it, "Come scrive l'AI? I 'tic linguistici' che svelano i bot".** https://blog.register.it/come-scrive-lai-i-tic-linguistici-che-svelano-i-bot/. Lineetta lunga, virgola seriale in aumento nei testi generati o tradotti, parallelismo negativo, lessico tipico. [§11, §14]
- **[DIV] Wikipedia, "Signs of AI writing"** (WikiProject AI Cleanup). https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing. Base della skill originale.

## Test interni

- **Connettivi causali (§9), 9 novembre 2026.** In un post di prova generato apposta, "Di conseguenza" faceva sembrare il calo dei costi un effetto del sondaggio dei dipendenti, mentre il testo mostrava solo che i due fatti erano avvenuti nello stesso periodo. La regola su causalità inventata e il relativo esempio vengono da questo test. Osservazione pratica, non studio.

## Come aggiornare

Quando aggiungi uno schema, indica qui la fonte e il livello di prova. Preferisci gli studi con un confronto diretto tra testi umani e generati nello stesso genere. Uno schema che si basa solo su impressioni va marcato *debole da solo* in SKILL.md.
