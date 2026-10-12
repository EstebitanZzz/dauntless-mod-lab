# Dauntless Mod Lab

**Pichudos Dev · Owner: Esteban Ocampo Chavarría**

[Portfolio](https://esteban-ocampo-pichudos-dev.estebitanz.chatgpt.site) · [Downloads / Descargas](https://github.com/EstebitanZzz/dauntless-mod-lab/releases)

## English

Personal modding projects for Dauntless Revived, developed through experimentation and AI-assisted development.

### Available download: DualSense + PlayStation prompts

The release ZIP includes compiled Win64 controller support, an INI configuration, a PlayStation prompt PAK and the SDL license. It does not include project source code, debug symbols, logs, credentials or the game itself.

- DualSense input over USB and Bluetooth, confirmed in-game on October 11, 2026.
- Conventional rumble and configurable touchpad click mapping.
- PlayStation button prompts; final coverage across game screens remains under validation.
- Built for the tested Dauntless Revived Win64 / Unreal Engine 4.25 installation. Compatibility with other builds is not established.

**Installation:** Close the game. Back up existing files with matching names. Do not overwrite an unrelated `XINPUT1_3.dll`. Copy the three runtime files in `DualSense/` (excluding the license) beside `Dauntless-Win64-Shipping.exe` in `Archon/Binaries/Win64`. Copy the PAK in `PlayStationPrompts/` to `Archon/Content/Paks`. Keep the SDL license with the package. Close DS4Windows and disable Steam Input to avoid duplicated controller input. See the ZIP's `README.txt` for removal and limitations.

One DualSense is supported. Adaptive triggers, advanced haptics, gyro and controller audio are not implemented.

### Discord Presence research

The wider project also includes detailed Discord presence for Ramsgate, hunts and escalations, a continuous session timer and nearby behemoth combat detection. Its Lua and PowerShell implementation is **not distributed in this repository**. Automated tests passed; combat detection still requires final in-game verification.

## Español

Proyectos personales de modding para Dauntless Revived, creados mediante experimentación y desarrollo con apoyo de IA.

### Descarga disponible: DualSense + iconos PlayStation

El ZIP contiene soporte de mando compilado para Win64, configuración INI, un PAK de iconos PlayStation y la licencia SDL. No contiene código fuente del proyecto, símbolos de depuración, registros, credenciales ni el juego.

- Entrada DualSense por USB y Bluetooth, confirmada dentro del juego el 11 de octubre de 2026.
- Vibración convencional y clic del touchpad configurable.
- Iconos de botones PlayStation; la cobertura final de las pantallas continúa en validación.
- Creado para la instalación probada de Dauntless Revived Win64 / Unreal Engine 4.25. No se ha establecido compatibilidad con otras versiones.

**Instalación:** Cierra el juego. Respalda los archivos existentes con esos nombres. No sobrescribas una `XINPUT1_3.dll` ajena. Copia los tres archivos de ejecución de `DualSense/` (excepto la licencia) junto a `Dauntless-Win64-Shipping.exe` en `Archon/Binaries/Win64`. Copia el PAK de `PlayStationPrompts/` a `Archon/Content/Paks`. Conserva la licencia SDL. Cierra DS4Windows y desactiva Steam Input para evitar entradas duplicadas. El `README.txt` del ZIP explica la desinstalación y limitaciones.

Admite un DualSense. No implementa gatillos adaptativos, háptica avanzada, giroscopio ni audio del mando.

### Investigación de presencia en Discord

El proyecto también incluye estados para Ramsgate, cacerías y escaladas, un temporizador continuo y detección de behemoths cercanos en combate. La implementación en Lua y PowerShell **no se distribuye en este repositorio**. Las pruebas automatizadas pasaron; falta la comprobación final del combate dentro del juego.

---

Independent fan project; not affiliated with or endorsed by the game's owners or Sony. Third-party components retain their respective licenses. Public documentation and compiled releases do not constitute a source-code license.

