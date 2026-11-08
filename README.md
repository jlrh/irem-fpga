# irem-fpga

Irem arcade cores for **MiSTer**. · Cores arcade de **Irem** para **MiSTer**.

| Game · Juego | Year · Año | Core | Alternatives · Alternativas |
|---|---|---|---|
| Beyond Kung-Fu (location test) | 1987 | `ffbkungfu` | |

## How to install

Copy the contents of [`_Arcade/`](_Arcade/) to the `_Arcade/` folder of your MiSTer SD card: the `.rbf` files go to
`_Arcade/cores/` and the `.mra` files to `_Arcade/`.

**ROMs are not included.** Bring your own MAME romset as `.zip` into `games/mame/`: `bkungfu.zip`.

## Cómo instalar

Copia el contenido de [`_Arcade/`](_Arcade/) a la carpeta `_Arcade/` de la SD de tu MiSTer: los `.rbf` van a
`_Arcade/cores/` y los `.mra` a `_Arcade/`.

**Las ROMs no se incluyen.** Pon tu propio romset de MAME en `.zip` en `games/mame/`: `bkungfu.zip`.

## Credits · Créditos

Original cores built on JTFRAME (Jose Tejada, GPLv3) and the MiSTer framework (`sys/`, GPLv2+). Third-party
components inside the `.rbf` files:

- **T80** Z80 CPU — Daniel Wallner (Verilog translation distributed with JTFRAME, Jose Tejada).
- **jt680x** M6803 sound CPU — Jose Tejada (GPLv3).
- **jt49** AY-3-8910 — Jose Tejada (GPLv3).
- **jt5205** MSM5205 ADPCM — Jose Tejada (GPLv3).

The MCU/blitter and the analog drums are implementations of their own. License: GPLv3 ([`LICENSE`](LICENSE)).

Cores originales sobre JTFRAME (Jose Tejada, GPLv3) y el framework de MiSTer (`sys/`, GPLv2+). Componentes de
terceros dentro de los `.rbf`: los de la lista anterior. La MCU/blitter y la batería analógica son implementaciones
propias. Licencia: GPLv3 ([`LICENSE`](LICENSE)).
