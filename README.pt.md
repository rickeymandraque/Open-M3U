🌍 **Idiomas**  
[🇬🇧 English](README.md) · [🇫🇷 Français](README.fr.md) · [🇪🇸 Español](README.es.md) · [🇮🇹 Italiano](README.it.md) · [🇵🇹 Português](README.pt.md)

---

## O que é o Open-M3U?

**Open-M3U** é um projeto aberto e orientado pela comunidade que documenta e melhora o uso real das **playlists M3U**, especialmente no contexto de **IPTV**.

As playlists M3U são amplamente utilizadas, mas **não existe uma especificação oficial** para tags e comportamentos específicos de IPTV.  
Como resultado, cada player, provedor ou ferramenta interpreta arquivos M3U de forma ligeiramente diferente.

O Open-M3U tem como objetivo:

- documentar as práticas existentes,
- identificar o que realmente funciona entre os players,
- e propor **perfis de padronização opcionais e pragmáticos**, baseados no uso real.

> O Open-M3U **não impõe um padrão obrigatório**.  
> Ele propõe convenções **documentadas, observáveis e testadas**.

---

## O que é um arquivo M3U?

Um **arquivo M3U** é uma playlist em texto simples que lista fluxos de mídia (áudio ou vídeo).

No IPTV, arquivos M3U são comumente usados para descrever:
- canais de TV
- transmissões de rádio
- serviços IPTV

Exemplo básico:

```m3u
#EXTM3U
#EXTINF:-1,Canal de exemplo
https://example.com/stream.m3u8
```

---

## Por que o Open-M3U existe?

Atualmente:

* não existe **um padrão oficial M3U para IPTV**,
* tags IPTV como `tvg-id`, `group-title` ou `catchup` não são documentadas,
* problemas de compatibilidade entre players são comuns (VLC, Kodi, TiviMate, etc.).

O Open-M3U fornece:

* uma **visão clara** do que existe,
* **fontes e referências** para cada comportamento,
* **perfis recomendados** para melhorar a compatibilidade.

---

## Estrutura do projeto

* **docs/** – documentação explicativa e para iniciantes
* **registry/** – tags e atributos M3U observados
* **profiles/** – perfis de padronização propostos (Core, IPTV Plus, etc.)
* **players/** – capacidades dos players (FFmpeg, VLC, Kodi, TiviMate…)
* **fixtures/** – playlists de teste reais
* **examples/** – scripts e exemplos simples

---

## Começando

Se você é novo:

* 📘 [O que é M3U?](docs/what-is-m3u.md)
* 🔤 [Codificação e finais de linha](docs/encoding-and-lines.md)
* 🧱 [Estrutura básica M3U](docs/basic-structure.md)
* 📖 [Glossário](docs/glossary.md)

---

## Contribuições

Contribuições são bem-vindas, especialmente se você fornecer:

* playlists reais ou casos de teste,
* referências de documentação ou código,
* comportamentos reproduzíveis nos players.

O Open-M3U valoriza **fatos acima de opiniões**.

---
