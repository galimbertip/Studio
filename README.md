# GPverse Studio

Web app per creare video YouTube (travel blog e non solo) da foto, video e musica — direttamente nel browser.

**Online:** https://galimbertip.github.io/Studio/

## Cosa fa
- Timeline di foto e video: riordina, dividi (✂), velocità 0,25×–4×
- ✨ Sottotitoli automatici in locale (Whisper) con stili animati, SRT, taglio dei silenzi
- Livelli liberi: testi, emoji e PNG trascinabili · voce fuori campo dal microfono
- 13 transizioni (tendina neon, glitch GPverse, zoom, cerchio…) ed effetto Ken Burns
- Testi animati, schede titolo con sfondo foto/collage, intro del canale e clip finale
- Colonna sonora con fade, loop e abbassamento automatico
- Pulsante **Iscriviti** animato e sonoro (Mi piace → Iscritto → campanella)
- Logo del canale in sovraimpressione
- Formati 16:9, Shorts 9:16, 1:1 fino a 1440p · export veloce MP4 (WebCodecs) + copertina PNG

## Uso in locale
Scarica `index.html` e aprilo con Chrome o Edge: funziona anche offline.
Foto e video restano sul tuo dispositivo; il progetto si salva nel browser.

## Versioni
Formato `Major.Minor.Patch` — vedi [CHANGELOG.md](CHANGELOG.md) e il file `VERSION`.
La versione è visibile anche nell'app (badge in alto).

## Crediti
- [Transformers.js](https://github.com/huggingface/transformers.js) © Hugging Face, Apache-2.0 (caricato da CDN solo quando generi i sottotitoli) e modelli Whisper di OpenAI (MIT)
- [mp4-muxer](https://github.com/Vanilagy/mp4-muxer) © Vanilagy, licenza MIT (incluso in `index.html`)
