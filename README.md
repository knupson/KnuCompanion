# KnuCompanion

App de escritorio para World of Warcraft: Forever. La dejás abierta en otro monitor y ves tus bolsas, tu banco, tu equipo, tu personaje en 3D, tus misiones, el chat y un mapa con tu posición y el camino hasta tu destino, mientras jugás.

Página: **[companion.knunet.com](https://companion.knunet.com)**, con capturas y la guía de instalación.

## Descarga

Bajá `KnuCompanion-win-Setup.exe` de [Releases](https://github.com/knupson/KnuCompanion/releases/latest) y ejecutalo. La app se instala y se actualiza sola.

1. Abrí KnuCompanion y elegí la carpeta de World of Warcraft.
2. Tocá **Instalar addon** y entrá al juego (o hacé `/reload`).

Sin instalar: bajá `KnuCompanion-win-Portable.zip`, descomprimilo entero en una carpeta propia y abrí `KnuCompanion.exe`.

## Qué hace falta

### Obligatorio

- Windows 10 u 11 de 64 bits.
- World of Warcraft: Forever.
- El addon **KnuCompanion**. Viene con la app y se instala con un botón. También está en CurseForge.

### Opcional

La app anda sin estos addons. Cada uno que tengas suma lo que dice la tabla:

| Addon | Qué agrega |
|---|---|
| FarstriderLib + FarstriderLib Data | Camino por las rutas hasta tu destino, con vuelos, barcos y portales |
| ShortestPathForever | Ruta por tramos si no tenés FarstriderLib |
| TomTom | El destino de la flecha en el mapa |
| Syndicator | Qué tiene cada uno de tus personajes sin conectarlo |
| Baganator | Categorías de Bolsas y Banco en el orden de Baganator |
| Auctionator | Precio de subasta en los tooltips |
| QuestieDB | Zonas de los objetivos de tus misiones en el mapa, y si tu objetivo es una criatura que te pide una misión |
| KnuJunk | Marcas de basura en las bolsas |
| HandyNotes (mazmorras, libros, WoW Forever) | Entradas de mazmorras, libros y raros en el mapa |

En la app, Engranaje → **Addons: obligatorio y opcionales…** muestra cuáles tenés.

## Otros addons de KNU / Other KNU addons

KnuCompanion es la pieza central de los addons KNU: la app junta en otro monitor lo que pasa en tu partida, y estos addons cuidan el resto dentro del juego.
KnuCompanion is the hub of the KNU addons: the app shows your game on a second monitor, and these addons handle the rest inside the game.

| Addon | Qué hace | What it does |
|---|---|---|
| [KnuUI](https://www.curseforge.com/wow/addons/knuui) | Interfaz compacta en ámbar para ElvUI | Compact amber layout for ElvUI |
| [KnuMail](https://www.curseforge.com/wow/addons/knumail) | Buzón simple y seguro | Simple, safe mailbox |
| [KnuJunk](https://www.curseforge.com/wow/addons/knujunk) | Marca y vende lo que no sirve, y repara solo | Marks and sells junk, repairs automatically |
| [KnuCast](https://www.curseforge.com/wow/addons/knucast) | Marca en las barras qué hechizos sirven contra el objetivo | Highlights which spells work against your target |

Todos los proyectos / All projects: [curseforge.com/members/knupwns/projects](https://www.curseforge.com/members/knupwns/projects)

## Qué toca en tu PC

La app lee la carpeta del juego. Escribe ahí sólo para instalar o actualizar el addon y para liberar en disco la parte de `Logs/General.log` que ya leyó (el archivo sigue ahí, sin ocupar espacio).

Este repo tiene sólo las versiones para descargar. Es una beta: si algo falla, abrí un issue.
