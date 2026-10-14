Halo CE — Universal Controller Mapping 🎮

Experimental controller mapping for Linux retro handhelds

Project maintained by SandFox91

Overview

This community project aims to improve controller mapping for Halo: Combat Evolved on Linux-based retro handheld consoles.

The main objective is simple: physical A, B, X and Y buttons should correspond to their respective Halo actions, without unwanted button inversion.

Controller Mapping

Physical button	Expected Halo input
A	A
B	B
X	X
Y	Y
L3	Preserve existing function
MENU + START	Preserve existing function

Compatibility

Device / Firmware	Status
G350 / Pan4Elec	V2 reported tested
G350 / Pan4Elec V3	Beta — testing required
ArkOS	Not yet verified
DARKOS	Not yet verified
Knulli	Not yet verified

Warning: Universal compatibility has not been established. Test the patch on your specific device and firmware before relying on it.

Installation

1. Back up your original sdl_mapping.py file.
2. Obtain the patch version intended for testing.
3. Review its instructions and compatibility requirements.
4. On supported installations, replace the appropriate mapping file.
5. Restart Halo CE.
6. Test A/B/X/Y, L3 and MENU + START.
7. Restore your backup if problems occur.

Do not install an unverified patch on an unsupported firmware without checking its controller configuration.

Languages / Langues / Idiomas / Sprachen / Языки

English: Experimental controller mapping correction for Halo CE. Back up the original file before installation.

Français : Correctif expérimental des commandes de Halo CE. Sauvegardez le fichier original avant installation.

Español: Corrección experimental de los controles de Halo CE. Guarda una copia del archivo original antes de instalar.

Deutsch: Experimentelle Controller-Anpassung für Halo CE. Sichere die Originaldatei vor der Installation.

Русский: Экспериментальное исправление управления для Halo CE. Перед установкой сохраните резервную копию исходного файла.

Credits

Original Halo CE port: kirklandsig/halo-ce-anbernic-rg35xx

Controller mapping adaptation and community testing: SandFox91.

This is an independent community project and is not an official Halo release.

Community Testing

Feedback is welcome, especially from ArkOS, DARKOS, Knulli and other Linux handheld users.

Please include your device model, firmware version, tested patch version and button test results when reporting issues.

Release Status

V3 — Experimental Beta

Further device testing and verification are required before a stable release.