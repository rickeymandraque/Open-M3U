🌍 **Langues**  
[🇬🇧 English](README.md) · [🇫🇷 Français](README.fr.md) · [🇪🇸 Español](README.es.md) · [🇮🇹 Italiano](README.it.md) · [🇵🇹 Português](README.pt.md)

---

## Qu’est-ce que Open-M3U ?

**Open-M3U** est un projet communautaire ouvert qui documente et améliore l’usage réel des **playlists M3U**, en particulier dans le contexte de l’**IPTV**.

Les playlists M3U sont largement utilisées, mais il n’existe **aucune spécification officielle** pour les balises et comportements spécifiques à l’IPTV.  
En conséquence, chaque lecteur, fournisseur ou outil interprète les fichiers M3U de manière légèrement différente.

Open-M3U a pour objectif de :

- documenter les pratiques existantes,
- identifier ce qui fonctionne réellement entre les lecteurs,
- et proposer des **profils de standardisation optionnels et pragmatiques**, basés sur des usages réels.

> Open-M3U n’impose **aucun standard obligatoire**.  
> Il propose des conventions **documentées, observables et testées**.

---

## Qu’est-ce qu’un fichier M3U ?

Un **fichier M3U** est une playlist en texte brut qui liste des flux multimédias (audio ou vidéo).

Dans l’IPTV, les fichiers M3U sont couramment utilisés pour décrire :
- des chaînes de télévision
- des flux radio
- des services IPTV

Exemple simple :

```m3u
#EXTM3U
#EXTINF:-1,Chaîne Exemple
https://example.com/stream.m3u8
```

---

## Pourquoi Open-M3U existe-t-il ?

Aujourd’hui :

* il n’existe **aucun standard officiel M3U pour l’IPTV**,
* les balises IPTV comme `tvg-id`, `group-title` ou `catchup` ne sont pas documentées,
* les problèmes de compatibilité entre lecteurs sont fréquents (VLC, Kodi, TiviMate, etc.).

Open-M3U fournit :

* une **vue claire** de l’existant,
* des **sources et références** pour chaque comportement observé,
* des **profils recommandés** pour améliorer l’interopérabilité.

---

## Structure du projet

* **docs/** – documentation explicative et débutant
* **registry/** – balises et attributs M3U observés
* **profiles/** – profils de standardisation proposés (Core, IPTV Plus, etc.)
* **players/** – capacités des lecteurs (FFmpeg, VLC, Kodi, TiviMate…)
* **fixtures/** – playlists de test réelles
* **examples/** – scripts et exemples simples

---

## Bien démarrer

Si vous débutez :

* 📘 [Qu’est-ce que M3U ?](docs/what-is-m3u.md)
* 🔤 [Encodage et fins de ligne](docs/encoding-and-lines.md)
* 🧱 [Structure de base M3U](docs/basic-structure.md)
* 📖 [Glossaire](docs/glossary.md)

---

## Contributions

Les contributions sont les bienvenues, notamment si vous fournissez :

* des playlists réelles ou des cas de test,
* des références de documentation ou de code,
* des comportements reproductibles sur les lecteurs.

Open-M3U privilégie les **faits aux opinions**.

---
