# Analisi del documento — "Software Totocalcio (data analysis exploration)"

> Sintesi strutturata del `.docx` originale. Documento di natura esplorativa: appunti e botta-e-risposta sull'idea di costruire un software/algoritmo per il Totocalcio.

## 1. Inquadramento del progetto
- Servirebbe un vero e proprio **corso di formazione** per spiegare tutto il know-how contenuto nei "faldoni" di appunti.
- Molte informazioni sono ricordate **a memoria** e spiegabili senza consultare i faldoni; le **matrici**, invece, sono indispensabili.
- Esistono software già pronti online, ma l'interesse vero è **capire il valore delle idee degli appunti**, frutto di esperienza diretta.

## 2. Software esistenti come riferimento
- La **versione gratuita** tipica sviluppa le colonne (numero totale di combinazioni), condizionabili con quadri AND/OR e link di recupero errori, **ma non visualizza** le colonne sviluppate.
- Software ipotizzato come riferimento: <https://www.totofortuna.it/scarica-software-totocalcio.php>
- Limite: poco rilevante installare un software se poi il sistema va comunque **convalidato in ricevitoria** dettando tutte le (molte) condizioni. Esistono anche versioni crackate, ma non è la strada di interesse.

## 3. Cosa deve fare il software/algoritmo desiderato
- Non solo input dati, ma **analisi statistica** + **algoritmo personalizzato** basato su metriche statistiche ricavate.
- Possibile lanciare **script Python da Excel** per data analysis e data visualization accurate.
- Deve prevedere: **quadri AND**, **quadri OR**, **quadri LINK** (valori di recupero).
- Funzione visiva chiave: mostrare il **calcolo delle colonne sottratte all'integrale** dopo l'inserimento di una condizione → **calcolo di convenienza** = rapporto tra taglio colonne e % di verifica della condizione.

## 4. Funzionamento del Totocalcio
### Attuale (ADM / Sisal)
- Descrizione gioco: <https://www.adm.gov.it/portale/descrizione-gioco-totocalcio>
- Come si gioca: <https://www.sisal.it/totocalcio/come-si-gioca>
- Si scommette su **7, 9, 11, 13, 14**.

### Formule (sistema attuale)
- **Formula 13**: prime **8 partite obbligatorie** (uguali per tutti) + **5 a scelta** su una lista di altre 12.
  → Statistica solo sulle **prime 8** (colonna vincente diversa per ogni giocatore).
- **Formula 9** = prime **6 obbligatorie** + 3 a scelta → statistica sulle prime 6.
- **Formula 11** = prime **7 obbligatorie** + 4 a scelta → statistica sulle prime 7.

### Classico a 14 (storico)
- Vecchio sistema basato su 13/12, poi 14. Partite **uguali per tutti**.
- Fonte 14 classico (fino al concorso della domenica precedente): <https://www.totoproject.com/giochi/Totocalcio_Stat_U50.asp>
- Quasi in disuso (montepremi bassi). Qualche giocata sul 13; interessanti le giocate sul **9** (vincite 4.000–7.000 €).
- **Da verificare in ricevitoria** se il 14 è ancora giocabile.

## 5. Idee statistiche dagli appunti
- **Vortici / "black hole"**: condizionamenti già presenti nei vecchi software (solo nomi diversi).
- **Somma dei segni** (1=1, X=2, 2=4): confronto tra **scarto colonnare** e **reale uscita** secondo criteri statistici.
- Strategia di risparmio (Formula/9): 9 triple condizionate + 5 segni fissi sulle ultime 5 partite.

## 6. Dati disponibili
- Database **bollettini ufficiali da gennaio 2022**, quasi tutte le settimane fino ad oggi.
- Storico uscite su tutti i 20 eventi: <https://giochi.softvision.it/Concorsi/Totocalcio/Anno-Concorsi-Totocalcio>

## 7. Link di riferimento (tutti)
| Tema | URL |
|------|-----|
| Strategia sistema ridotto (generico) | https://www.esperimentanda.com/come-vincere-al-totocalcio-con-un-sistema-ridotto-strategia-per-giocare-schedina/ |
| Introduzione sistemistica | https://giochi.softvision.it/Sistemi/Introduzione-Sistemistica-Totocalcio |
| Forum wheels | https://wheels.forumcommunity.net/?t=60826502 |
| Video YouTube (Pronostici Naturali) + blog con Excel | https://www.youtube.com/watch?v=6VYZIinzsYI |
| Software Totofortuna | https://www.totofortuna.it/scarica-software-totocalcio.php |
| Descrizione gioco ADM | https://www.adm.gov.it/portale/descrizione-gioco-totocalcio |
| Come si gioca (Sisal) | https://www.sisal.it/totocalcio/come-si-gioca |
| Storico concorsi (Softvision) | https://giochi.softvision.it/Concorsi/Totocalcio/Anno-Concorsi-Totocalcio |
| Statistiche 14 classico (Totoproject) | https://www.totoproject.com/giochi/Totocalcio_Stat_U50.asp |

## 8. Punti aperti / da chiarire
- I metodi basati su **Excel** citati nei link non sono chiari → servono spiegazioni.
- Incertezza sull'ultimo link (14 classico): è l'unico sulla schedina classica a 14, gli altri riguardano le Formule.
- Verifica diretta in **ricevitoria** consigliata su più fronti.
