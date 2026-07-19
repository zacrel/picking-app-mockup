# Warehouse Picking · Mock-up

Mock-up interattivo responsive per la presentazione al cliente del flusso di prelievo ordini.

## Funzioni simulate

- autenticazione dell'operatore tramite PIN numerico;
- elenco delle picking list disponibili;
- liste ordinate per SKU o numero ordine;
- visualizzazione di stato e avanzamento;
- prelievo guidato articolo per articolo;
- simulazione della scansione barcode;
- riconoscimento di articolo errato o appartenente a un altro ordine;
- salto di un articolo e ripresa di una lista non completata.

## Avvio locale

Aprire `index.html` con un browser moderno. Non sono richiesti installazione, backend o processo di compilazione.

## Pubblicazione su GitHub Pages

1. Caricare `index.html`, `README.md` e `.nojekyll` nella radice del branch `main`.
2. Aprire **Settings → Pages** nel repository.
3. Selezionare **Deploy from a branch**.
4. Impostare il branch `main` e la cartella `/(root)`.
5. Premere **Save** e attendere la pubblicazione.

## Nota

Tutti i dati mostrati sono dimostrativi. Il PIN e la scansione barcode simulano soltanto il comportamento dell'interfaccia e non implementano autenticazione o lettura ottica reali.
