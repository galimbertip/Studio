# Changelog — GPverse Studio

Versioni nel formato **Major.Minor.Patch**: Major = cambi grossi o incompatibili, Minor = nuove funzioni, Patch = correzioni.

## v1.5.0 — 2026-11-11 · "Tutti i formati + Kit del brand"
- ⚙ Impostazioni divise in schede: Brand, Canale & Social, Export, App
- Kit del brand (nome, handle, avatar, logo, colori, font, Iscriviti, intro, finale) applicato a ogni nuovo progetto
- Profili social con controllo dell'indirizzo e hashtag del canale (base per il Social Kit) — nessuna password salvata, per scelta
- Export multiplo in un clic: 16:9, 9:16, 1:1 e nuovo 4:5 (feed Instagram)
- Punto focale per foto e video nei formati ritagliati
- Backup/ripristino delle impostazioni in JSON; "Nuovo progetto" conserva logo e avatar del brand

## v1.4.0 — 2026-11-10 · "Sottotitoli AI"
- ✨ Sottotitoli automatici con Whisper (transformers.js) eseguito sul dispositivo: nessun upload, nessun credito
- Modelli Tiny / Base / Small / Turbo (WebGPU), 6 lingue + rilevamento automatico
- 5 stili animati: Karaoke, Riquadro sulla parola, Pop, Neon GPverse, Classico TV
- Righe modificabili, ritardo regolabile, parole per riga, MAIUSCOLO
- Importa/esporta SRT e VTT, copia negli appunti
- ✂ Taglio automatico dei silenzi nei video (jump-cut)

## v1.3.0 — 2026-11-10 · "Editor vero"
- ✂ Dividi le clip alla testina (pulsante o tasto S)
- Velocità video da 0,25× a 4×
- Scheda **Livelli**: testi liberi, emoji e immagini PNG con tempi propri, trascinabili sull'anteprima
- Stili testo: riquadro, ombra, contorno, neon, evidenziatore · animazioni pop, sale, macchina da scrivere
- 🎙 Voce fuori campo registrata dal microfono (o da file), con abbassamento automatico della musica
- ⚡ Export veloce WebCodecs (H.264/VP9 + AAC/Opus in MP4) che funziona anche in background; il tempo reale resta come alternativa
- Corsia dei livelli sotto la timeline con testina di riproduzione
- Include [mp4-muxer](https://github.com/Vanilagy/mp4-muxer) v5.2.2 (MIT) per creare i file MP4

## v1.2.0 — 2026-11-08
- Schede con sfondo personalizzato: una foto o un collage fino a 6 foto, con oscuramento e sfocatura
- Font, dimensione e colore separati per titolo e sottotitolo (su tutte le clip)
- Nuova clip **Intro del canale**: logo con onda d'urto, nome che si scrive, 3 stili (Neon, Cinema, Viaggio)
- Nuova clip **Finale** stile schermata finale YouTube: riquadri per i video consigliati e cerchio Iscriviti
- Effetti sonori sintetizzati: pop, clic, Mi piace, Iscritto e campanella; whoosh e impatto nell'intro
- Toccando i brani nella timeline si apre la scheda Musica

## v1.1.0 — 2026-11-08
- Logo del canale in sovraimpressione in un angolo (PNG trasparenti supportati)
- Forma originale, cerchio o quadrato arrotondato · dimensione, opacità e bagliore neon
- Il logo entra ed esce in dissolvenza; watermark e pulsante Iscriviti si spostano se sono nello stesso angolo

## v1.0.0 — 2026-11-08
- Prima release: timeline foto + video, 13 transizioni, Ken Burns, sfondo sfocato per foto verticali
- Testi animati (banda, titolo, luogo, macchina da scrivere, neon) e schede titolo synthwave/bokeh
- Playlist musicale con fade, loop e abbassamento automatico sui video
- Pulsante Iscriviti animato: Mi piace → Iscritto → campanella
- Formati 16:9, 9:16 Shorts, 1:1 · 720p/1080p/1440p · 24/30/60 fps
- Export MP4/WebM e copertina PNG · salvataggio automatico e annulla
