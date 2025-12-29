🌍 **Idiomas**  
[🇬🇧 English](README.md) · [🇫🇷 Français](README.fr.md) · [🇪🇸 Español](README.es.md) · [🇮🇹 Italiano](README.it.md) · [🇵🇹 Português](README.pt.md)

---

## ¿Qué es Open-M3U?

**Open-M3U** es un proyecto comunitario abierto que documenta y mejora el uso real de las **listas M3U**, especialmente en el contexto de **IPTV**.

Las listas M3U se utilizan ampliamente, pero **no existe una especificación oficial** para las etiquetas y comportamientos específicos de IPTV.  
Como resultado, cada reproductor, proveedor o herramienta interpreta los archivos M3U de forma ligeramente diferente.

Open-M3U tiene como objetivo:

- documentar las prácticas existentes,
- identificar qué funciona realmente entre reproductores,
- y proponer **perfiles de estandarización opcionales y pragmáticos**, basados en el uso real.

> Open-M3U **no impone un estándar obligatorio**.  
> Propone convenciones **documentadas, observables y probadas**.

---

## ¿Qué es un archivo M3U?

Un **archivo M3U** es una lista de reproducción en texto plano que enumera flujos multimedia (audio o vídeo).

En IPTV, los archivos M3U se utilizan comúnmente para describir:
- canales de televisión
- transmisiones de radio
- servicios IPTV

Ejemplo básico:

```m3u
#EXTM3U
#EXTINF:-1,Canal de ejemplo
https://example.com/stream.m3u8
```

---

## ¿Por qué existe Open-M3U?

Hoy en día:

* no existe **un estándar oficial M3U para IPTV**,
* las etiquetas IPTV como `tvg-id`, `group-title` o `catchup` no están documentadas,
* los problemas de compatibilidad entre reproductores son frecuentes (VLC, Kodi, TiviMate, etc.).

Open-M3U proporciona:

* una **visión clara** de lo que existe,
* **fuentes y referencias** para cada comportamiento,
* **perfiles recomendados** para mejorar la compatibilidad.

---

## Estructura del proyecto

* **docs/** – documentación explicativa y para principiantes
* **registry/** – etiquetas y atributos M3U observados
* **profiles/** – perfiles de estandarización propuestos (Core, IPTV Plus, etc.)
* **players/** – capacidades de los reproductores (FFmpeg, VLC, Kodi, TiviMate…)
* **fixtures/** – listas de prueba reales
* **examples/** – scripts y ejemplos simples

---

## Primeros pasos

Si eres nuevo:

* 📘 [¿Qué es M3U?](docs/what-is-m3u.md)
* 🔤 [Codificación y finales de línea](docs/encoding-and-lines.md)
* 🧱 [Estructura básica M3U](docs/basic-structure.md)
* 📖 [Glosario](docs/glossary.md)

---

## Contribuciones

Las contribuciones son bienvenidas, especialmente si proporcionas:

* listas reales o casos de prueba,
* referencias a documentación o código,
* comportamientos reproducibles en reproductores.

Open-M3U valora los **hechos por encima de las opiniones**.

---
