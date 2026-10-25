# Claude-Ai

Assistente a mani libere per Especially Puglia e Masseria Pietra e Terra:
tu parli, Claude legge Omi e Plaud, apre i reparti e agisce chiedendo conferma.

## Prompt

- [`prompts/briefing-mattutino.md`](prompts/briefing-mattutino.md): briefing di
  ogni mattina con 3-5 priorità e 4 domande per punto.
- [`prompts/direttore-vocale.md`](prompts/direttore-vocale.md): regole per la
  modalità vocale hands off (reparti, comandi, conferme).

## Come usarli

1. Nell'app Claude crea un Progetto, per esempio "Briefing".
2. Incolla nelle istruzioni del Progetto il briefing e, sotto, il Direttore.
3. Attiva i connettori: Omi, Plaud, Asana, Google Calendar, Gmail, Missive,
   Octorate, Zoho Books.
4. Apri una chat nel Progetto in modalità vocale e di' "Iniziamo il briefing".

## Omi o Plaud

- **Omi**: sempre acceso. Idee e comandi al volo, contesto della giornata.
- **Plaud**: lo accendi tu. Riunioni, telefonate, incontri.

## Controllo del computer

1. **Connettori** (Missive, Asana, Zoho, Google Drive, Calendar): Claude lavora
   sui dati senza aprire le app. È sempre la prima scelta.
2. **Claude in Chrome**: per i siti senza connettore, per esempio ShipStation.
3. **Computer use** (app desktop di Claude): apre e chiude le app sul computer.
   Permessi dati app per app; mai a banca o dati personali.

## Simulatore del briefing

`simulator/briefing-simulator.html`: il briefing come slide, una domanda per
slide, presa dalle conversazioni Omi. Rispondi a voce, "next" chiude il punto e
passa al successivo; alla fine un riepilogo da copiare in Claude per creare o
aggiornare i task in Asana. Per registrare la voce apri il file con Chrome o
Edge sul computer, premi "Start recording" e consenti il microfono.
