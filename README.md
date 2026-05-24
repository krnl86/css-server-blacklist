# CSS Server Blacklist

> A community-maintained blacklist of Counter-Strike: Source servers known for running cheats, aimbots, unfair plugins, or otherwise ruining the gameplay experience.

---

## 🇺🇸 English

### What is this?

This repository contains a `server_blacklist.txt` file compatible with Counter-Strike: Source. It blocks known malicious or heavily modified servers that bypass fair play — including servers running aim assistance, wallhacks, unfair advantages, or disruptive plugins.

The list currently contains **7,644 unique entries** (identified by `ip:port`), with no duplicates.

### How to use it

1. Download the `server_blacklist.txt` file from this repository.
2. Place it in your CS:S config directory:
   ```
   Steam/steamapps/common/Counter-Strike Source/cstrike/cfg/
   ```
3. Launch the game — the blacklist is loaded automatically.

> If you already have a blacklist file, make sure to merge the entries rather than replacing the file entirely to avoid losing your existing blocks.

### How to contribute

Found a server that should be on this list? Open an [Issue](../../issues/new) with:
- The server's `ip:port`
- The server name (as it appears in the browser)
- A brief reason (e.g. *aimbot plugin*, *fake player count*, *wall exploit*)

Pull requests with additions are also welcome.

### Credits & Inspiration

This project was inspired by and built upon the work of **[Ballganda](https://github.com/Ballganda/css-server-blacklist)**, whose original blacklist laid the groundwork for community-driven server filtering in CS:S.

### License

This project is distributed under the **GNU General Public License v3.0** — see the [`LICENSE`](LICENSE) file for full terms.

It is based on work by **Ballganda**, originally licensed under **GPL-2.0-or-later**. A copy of the original license is included in [`LICENSES/GPL-2.0.txt`](LICENSES/GPL-2.0.txt) for attribution and compliance purposes.

```
Upstream work:  GPL-2.0-or-later  (Ballganda/css-server-blacklist)
This repository: GPL-3.0-or-later  (krnl86/css-server-blacklist)
```

---

## 🇪🇸 Español

### ¿De qué trata este proyecto?

Este repositorio mantiene un archivo `server_blacklist.txt` para Counter-Strike: Source, diseñado para bloquear servidores que utilizan trampas, plugins injustos, aimbots u otras modificaciones que arruinan la experiencia de juego para el resto de la comunidad.

La lista cuenta actualmente con **7,644 entradas únicas** (identificadas por `ip:puerto`), sin repeticiones.

### ¿Cómo se instala?

1. Descarga el archivo `server_blacklist.txt` de este repositorio.
2. Colócalo dentro de la carpeta de configuración de CS:S:
   ```
   Steam/steamapps/common/Counter-Strike Source/cstrike/cfg/
   ```
3. Inicia el juego — la lista se carga de forma automática.

> Si ya tienes un archivo de blacklist propio, se recomienda combinar las entradas en lugar de reemplazar el archivo para no perder tus bloqueos existentes.

### ¿Cómo puedo colaborar?

Si encontraste un servidor que debería estar en la lista, abre un [Issue](../../issues/new) con la siguiente información:
- La dirección `ip:puerto` del servidor
- El nombre del servidor tal como aparece en el navegador de juegos
- Una breve justificación (ej: *aimbot activo*, *conteo falso de jugadores*, *exploit de mapa*)

También se aceptan pull requests con nuevas entradas.

### Créditos

Este proyecto está inspirado en el trabajo de **[Ballganda](https://github.com/Ballganda/css-server-blacklist)**, cuya lista original sentó las bases para el filtrado colaborativo de servidores en CS:S. Sin su esfuerzo previo, este repositorio no existiría.

### Licencia

Este repositorio se distribuye bajo la **Licencia Pública General de GNU v3.0** — consulta el archivo [`LICENSE`](LICENSE) para ver los términos completos.

Está basado en el trabajo de **Ballganda**, publicado originalmente bajo **GPL-2.0-or-later**. Se incluye una copia de dicha licencia en [`LICENSES/GPL-2.0.txt`](LICENSES/GPL-2.0.txt) con fines de atribución y cumplimiento legal.

```
Proyecto original:  GPL-2.0-or-later  (Ballganda/css-server-blacklist)
Este repositorio:   GPL-3.0-or-later  (krnl86/css-server-blacklist)
```
