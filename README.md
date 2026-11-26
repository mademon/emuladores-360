![La Pandilla Retro](assets/la-pandilla-retro.png)

# Emuladores 360 + Autoboot

Emuladores para Xbox 360 con RGH (Aurora) que arrancan directo al juego, sin pasar por el menú del emulador. Cada juego tiene su propia carpeta con su emulador y su juego, y aparece en Aurora como un juego más.

## Sistemas incluidos

- **PS1** — SwanStation (juegos en .chd)
- **GBA** — VBA-M (juegos en .gba / .gb / .gbc)
- **NES** — FCEUmm (juegos en .nes / .fds)
- **SNES** — Snes9x (juegos en .smc / .sfc)
- **Sega** — Genesis Plus GX (Genesis .md y Sega CD .chd / .cue)
- **FBA** — Final Burn Alpha (arcade .zip, set 0.2.97.40)

Además trae el **Lanzador Unificado**, un solo menú para todos los sistemas, con temas (Pandora Box, Clásico, Carbon y Mega Pixel), y los filtros de Aurora para ver cada sistema en su propio apartado.

## Descarga

Ve a **Releases** y baja solo el zip del sistema que quieras, uno por sistema:

- **PS1-Emulador-y-Autoboot.zip** — emulador SwanStation + plantilla autoboot (juego fijo `game.chd`)
- **GBA-Emulador-y-Autoboot.zip** — emulador VBA-M + plantilla autoboot (juego fijo `game.gba`)
- **NES-Emulador-y-Autoboot.zip** — emulador FCEUmm + plantilla autoboot (juego fijo `game.nes`)
- **SNES-Emulador-y-Autoboot.zip** — emulador Snes9x + plantilla autoboot (juego fijo `game.smc`)
- **Sega-Emulador-y-Autoboot.zip** — emulador Genesis Plus GX + plantilla autoboot (Genesis `game.md`, Sega CD `game.chd`)
- **FBA-Emulador.zip** — emulador arcade Final Burn Alpha (lista de juegos, no es autoboot)
- **Lanzador-Unificado-v1.3.zip** — el Lanzador Unificado (un solo menú para los 7 sistemas)
- **Aurora-y-Tutorial.zip** — filtros de Aurora por sistema + tutorial paso a paso en Word

Cada zip trae su LEEME corto con lo necesario, sin rollo. Ningún zip trae juegos ni BIOS: cada quien pone los suyos (así no pesan y no hay broncas de derechos).

## Instalación rápida

1. Baja el zip del sistema que quieras y descomprímelo.
2. Cada emulador va en su carpeta dentro de `Hdd1:\Emuladores\`.
3. Para los autoboot: cada juego va en su propia carpeta `Hdd1:\<Sistema>\<Juego>\` junto con su xex autoboot (ver el tutorial).
4. En Aurora, escanea el contenido y usa los filtros incluidos para ver cada sistema en su apartado.

El tutorial completo (`TUTORIAL-Autoboot-360.docx`) viene en el zip `Aurora-y-Tutorial.zip`.

## Créditos

Hecho por **Nina-Mon**.
Nina-Mon somos Nina (IA) y Mademon (Humano).

## Agradecimientos

Estos paquetes no serían posibles sin el trabajo de los creadores originales de cada emulador. Gracias a:

- **PS1 — SwanStation**: fork de DuckStation (de stenzek) para libretro, mantenido por la comunidad de libretro. Código fuente: https://github.com/libretro/swanstation
- **PS1 (port a Xbox 360) — swanstation-xenon**: por xenosworks. Código fuente: https://github.com/xenosworks/swanstation-xenon
- **GBA — VBA-M**: por el equipo de VBA-M. Código fuente: https://github.com/visualboyadvance-m/visualboyadvance-m
- **NES — FCEUmm**: core libretro basado en FCEUX, por el equipo de FCEUX y la comunidad de libretro. Código fuente: https://github.com/libretro/libretro-fceumm
- **SNES — Snes9x**: por el equipo de Snes9x (Gary Henderson, Jerremy Koot y colaboradores). Código fuente: https://github.com/snes9xgit/snes9x
- **Sega — Genesis Plus GX**: por EkeEke, basado en Genesis Plus de Charles MacDonald. Código fuente: https://github.com/ekeeke/Genesis-Plus-GX
- **FBA — FinalBurn Alpha**: por el equipo de FinalBurn Alpha (Barry Harris, dink, iq_132 y la comunidad), basado en FinalBurn de Dave. Código fuente: https://github.com/libretro/fbalpha
- **Lanzador Unificado**: hecho por Nina-Mon sobre el host de xenosworks (swanstation-xenon). Código fuente: https://github.com/xenosworks/swanstation-xenon
- **Aurora**: dashboard para Xbox 360 con RGH creado por el equipo Phoenix (Aurora es de código cerrado, por eso no se incluye su código fuente).

Y gracias a **La Pandilla Retro**, el equipo que colabora con Nina-Mon en la construcción de estos proyectos.

## Avances

Aquí iremos subiendo los avances del proyecto: nuevas versiones de los emuladores, el lanzador y las plantillas autoboot.
