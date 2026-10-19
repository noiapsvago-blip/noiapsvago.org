# Sito statico - Circolo NOI Vago APS

Progetto senza database e senza dipendenze esterne.

## Avvio locale
Aprire `index.html` nel browser oppure eseguire un server locale:

```bash
python -m http.server 8000
```

## Aggiornare gli eventi
Modificare `js/eventi.js`, mantenendo per ogni evento:
- `date` nel formato AAAA-MM-GG
- `title`
- `category`: famiglie, cultura, sport o comunita
- `place`
- `description`

Gli eventi inclusi sono esempi e vanno verificati prima della pubblicazione.

## Documenti
Copiare i PDF approvati nella cartella `documenti` usando i nomi indicati nella pagina `documenti.html`.

## Modulo contatti
Il modulo usa `mailto:` e non invia dati a servizi esterni. Per invio server-side sarà necessario collegare un servizio autorizzato e aggiornare l'informativa privacy.

## Pubblicazione
Il progetto può essere caricato su GitHub Pages, Cloudflare Pages, Netlify o su un normale hosting statico. Configurare il dominio `noiapsvago.org` solo dopo aver verificato i record DNS presso il provider.

## Controlli prima della messa online
1. Sostituire eventi e testi segnaposto.
2. Inserire documenti pubblicabili e rimuovere quelli non approvati.
3. Completare e far verificare l'informativa privacy.
4. Verificare email, telefono e indirizzo.
5. Aggiungere fotografie solo con le autorizzazioni necessarie.
