🌍 **Lingue**  
[🇬🇧 English](README.md) · [🇫🇷 Français](README.fr.md) · [🇪🇸 Español](README.es.md) · [🇮🇹 Italiano](README.it.md) · [🇵🇹 Português](README.pt.md)

---

## Cos’è Open-M3U?

**Open-M3U** è un progetto open e guidato dalla comunità che documenta e migliora l’uso reale delle **playlist M3U**, in particolare nel contesto **IPTV**.

Le playlist M3U sono ampiamente utilizzate, ma **non esiste una specifica ufficiale** per i tag e i comportamenti specifici IPTV.  
Di conseguenza, ogni player, provider o strumento interpreta i file M3U in modo leggermente diverso.

Open-M3U mira a:

- documentare le pratiche esistenti,
- identificare ciò che funziona realmente tra i player,
- e proporre **profili di standardizzazione opzionali e pragmatici**, basati sull’uso reale.

> Open-M3U **non impone uno standard obbligatorio**.  
> Propone convenzioni **documentate, osservabili e testate**.

---

## Cos’è un file M3U?

Un **file M3U** è una playlist in testo semplice che elenca flussi multimediali (audio o video).

Nel contesto IPTV, i file M3U sono comunemente usati per descrivere:
- canali TV
- flussi radio
- servizi IPTV

Esempio di base:

```m3u
#EXTM3U
#EXTINF:-1,Canale di esempio
https://example.com/stream.m3u8
```

---

## Perché esiste Open-M3U?

Oggi:

* non esiste **uno standard ufficiale M3U per IPTV**,
* i tag IPTV come `tvg-id`, `group-title` o `catchup` non sono documentati,
* i problemi di compatibilità tra i player sono comuni (VLC, Kodi, TiviMate, ecc.).

Open-M3U fornisce:

* una **panoramica chiara** di ciò che esiste,
* **fonti e riferimenti** per ogni comportamento,
* **profili consigliati** per migliorare l’interoperabilità.

---

## Struttura del progetto

* **docs/** – documentazione esplicativa e per principianti
* **registry/** – tag e attributi M3U osservati
* **profiles/** – profili di standardizzazione proposti (Core, IPTV Plus, ecc.)
* **players/** – capacità dei player (FFmpeg, VLC, Kodi, TiviMate…)
* **fixtures/** – playlist di test reali
* **examples/** – script ed esempi semplici

---

## Per iniziare

Se sei nuovo:

* 📘 [Cos’è M3U?](docs/what-is-m3u.md)
* 🔤 [Codifica e fine riga](docs/encoding-and-lines.md)
* 🧱 [Struttura base M3U](docs/basic-structure.md)
* 📖 [Glossario](docs/glossary.md)

---

## Contributi

I contributi sono benvenuti, soprattutto se fornisci:

* playlist reali o casi di test,
* riferimenti a documentazione o codice,
* comportamenti riproducibili sui player.

Open-M3U valorizza i **fatti rispetto alle opinioni**.

---
