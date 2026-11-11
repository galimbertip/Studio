# Roadmap — GPverse Studio → GPverse Hub

Versioni nel formato **Major.Minor.Patch**. Questo file è la coda dei lavori: si aggiorna a ogni release.

## Fatto
- **v1.0 – v1.2** Montaggio foto/video, transizioni, musica, Iscriviti animato, logo, intro, finale, collage
- **v1.3** Editor vero: dividi, velocità, livelli (testi/emoji/PNG), voce fuori campo, export veloce WebCodecs
- **v1.4** Sottotitoli automatici in locale (Whisper), stili animati, SRT, taglio dei silenzi
- **v1.5** Impostazioni a schede, kit del brand, profili social, export multiplo 16:9/9:16/1:1/4:5, punto focale

## In coda
- **v1.6 – Social Kit** (pensato come modulo condiviso, poi entra nel Hub)
  - Un "contenuto" = video + post per ogni piattaforma (YouTube, Shorts, Instagram post/Reel/Storia, TikTok, Facebook)
  - Regole per piattaforma con controlli in tempo reale: lunghezza testi, hashtag, formato/durata del video
    (es. Instagram max 5 hashtag dal dic 2025; YouTube titolo 100, descrizione 5000, max 15 hashtag; TikTok/IG didascalia 2200)
    Le regole stanno in una tabella aggiornabile, perché i social le cambiano spesso.
  - Anteprima di come apparirà il post, libreria di hashtag e testi ricorrenti, set di Storie (9:16) generate dal video
  - Pubblicazione assistita: dal telefono "Condividi" apre direttamente l'app (Instagram, TikTok, YouTube) col video,
    il testo viene copiato; dal PC: scarica + copia campo per campo + apre la pagina di caricamento
  - Piano di pubblicazione con date e promemoria nel calendario (.ics)
  - Pubblicazione diretta via API: da valutare dopo (vedi note)
- **v1.7 – Strumenti da travel creator**: mappa animata del percorso, luoghi e date dai dati delle foto, modelli "recap del viaggio"
- **v2.0 – GPverse Hub**: un'unica app installabile (PWA) che unisce Studio + OnAir (podcast) + Discoremix (remix/canzoni) + Social Kit,
  con libreria media condivisa, kit del brand unico, calendario editoriale unico e salvataggio progetti su file

## Note sulla pubblicazione diretta (verificate a novembre 2026)
- **YouTube**: i video caricati via API da progetti Google non verificati restano privati e non si possono rendere pubblici → serve l'audit di Google.
- **TikTok**: le app non verificate possono pubblicare solo in privato; l'audit richiede un'app per un pubblico ampio, non per uso personale.
- **Instagram**: possibile per il proprio account Business/Creator, ma il file deve essere su un server pubblico e le Storie solo da account Business.
- Quindi per uso personale la strada migliore è la **pubblicazione assistita**; l'API diretta ha senso solo se il prodotto diventa pubblico.
