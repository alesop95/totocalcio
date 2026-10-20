# Progetto: Software Totocalcio — Data Analysis & Algoritmo

## Obiettivo
Non si vuole semplicemente installare un software esistente per inserire dati, ma:
1. Costruire un **dataset** dei bollettini ufficiali del Totocalcio.
2. Fare **analisi statistica** (data analysis + data visualization).
3. Derivare metriche statistiche e costruire un **algoritmo personalizzato** di pronostico/condizionamento delle colonne.

Fase attuale = **preliminare/esplorativa**. La spiegazione delle idee degli appunti è più chiara "con un software aperto" che mostri visivamente i calcoli (es. colonne sottratte all'integrale dopo l'inserimento di una condizione).

## Concetti chiave del dominio
- **Sviluppo colonne**: numero totale di combinazioni, poi condizionato tramite:
  - **Quadri AND**, **Quadri OR**, **Quadri LINK** (gestione valori di recupero errori).
- **Calcolo di convenienza**: rapporto fra taglio delle colonne e percentuale di verifica della condizione inserita.
- **Terminologia**: i "vortici" nei vecchi software = "black hole".
- **Somma dei segni**: 1=1, X=2, 2=4 — confronto tra scarto colonnare e reale uscita secondo criteri statistici.
- Sistema **vecchio** Totocalcio = basato su 13/12 (poi 14). Sistema **attuale** = diverso (Formule).

## Modalità di gioco (attuale) e dove fare statistica
La statistica va sempre condotta sulle **partite obbligatorie comuni a tutti i giocatori** (le altre sono a scelta del singolo → colonne vincenti diverse).

| Formula | Partite obbligatorie | Partite a scelta | Statistica sulle prime |
|---------|----------------------|------------------|------------------------|
| Formula 13 | 8 | 5 (su lista di 12) | 8 |
| Formula 11 | 7 | 4 | 7 |
| Formula 9  | 6 | 3 | 6 |
| Classico 14 | 14 (uguali per tutti) | — | 14 |

- Si scommette su **7, 9, 11, 13, 14**.
- Per la **9**: possibile giocare 9 triple condizionate + fissare 5 segni sulle ultime 5 partite → forte risparmio di colonne e costi. Vincite osservate 4.000–7.000 €.
- Il **14 classico** è quasi in disuso (montepremi bassi); qualche giocata sul 13. **Da verificare in ricevitoria** se il 14 è ancora giocabile.

## Dati
- Database bollettini ufficiali disponibile **da gennaio 2022**, quasi tutte le settimane fino ad oggi.
- I sistemi vanno comunque convalidati in **ricevitoria**, dettando tutte le condizioni imposte.

## Stato / TODO
- [ ] Definire schema del dataset bollettini (da gennaio 2022).
- [ ] Verificare in ricevitoria: giocabilità del 14 classico e dettaglio condizioni accettate.
- [ ] Chiarire i metodi Excel citati nei link (poco chiari, servono spiegazioni).
- [ ] Prototipo visivo: calcolo colonne sottratte all'integrale dopo una condizione.

Vedi `docs/analisi-totocalcio.md` per l'analisi dettagliata e tutti i link di riferimento.

Norme caricate su richiesta, una riga per situazione con le parole con cui si presenta, così che il caricamento non dipenda dal ricordare che la norma esista.

- `git worktree list` mostra più di un albero, se ne crea o se ne rimuove uno, si deve decidere da dove leggere la memoria versionata: skill `alberi-di-lavoro`.
- Un recupero web fallisce con 403 o con una pagina di verifica anti-bot, la fonte sta su Reddit o su Discord, serve la trascrizione di un video, si sta per annotare una fonte non letta: skill `fonti-non-recuperabili`.
- Si scrive o si valuta una prova automatica, si chiude un difetto, una verifica manuale smentisce una suite verde, si sta per dichiarare completo un intervento il cui scopo era un effetto misurabile: skill `prove-che-misurano`.
- Si inizializza o si allinea il progetto, oppure cambia il modo in cui si prova e si rilascia, e va deciso come separare test e produzione: skill `separazione-ambienti`.
- Si imposta o si verifica user.name e user.email, si collega o si cambia il remoto o l'alias SSH, si inizializza un repository, un push fallisce per permessi, `/status` mostra un account Claude diverso da quello atteso, si autentica o si usa `gh`: skill `identita-git`.
- Va prodotto, modificato o convertito un artefatto visivo o documentale, cioè un documento, una presentazione, un PDF, un'immagine, un'animazione, un audio o un impaginato, oppure si sta per scrivere uno script o installare una libreria per farlo: skill `craft-apps`, che prima verifica in locale le applicazioni Craft installate e le usa senza rete né token.
