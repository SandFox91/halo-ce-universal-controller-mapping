Halo CE — Universal Controller Mapping 🎮

Controller mapping correction for Linux retro handhelds.

Project maintained by SandFox91.

Overview

This community project aims to improve controller mapping for Halo: Combat Evolved on Linux-based retro handheld consoles.

The objective is to correct unwanted button inversions and provide consistent controller behavior.

V3 Beta has been tested and confirmed working on the G350 running Pan4Elec.

Compatibility with other custom firmwares still requires community testing.

Controller Mapping

The V3 Beta patch aims to provide the following behavior:

* A: Correct A button mapping.
* B: Correct B button mapping.
* X: Correct X button mapping.
* Y: Correct Y button mapping.
* L3: Preserve the existing function.
* MENU + START: Preserve the existing function.

Compatibility

* G350 / Pan4Elec — V3 Beta: Tested and working.
* ArkOS: Not yet verified.
* DARKOS: Tested — the original Halo CE port does not launch and returns directly to EmulationStation. Controller mapping could not be tested.
* Knulli: Not yet verified.
* Other Linux custom firmwares: Not yet verified.

Universal compatibility has not been established. Please report results only from devices and firmware versions you have actually tested.

Installation — Pan4Elec G350

1. Download the V3 Beta ZIP archive from the GitHub Releases page.
2. Extract the ZIP archive.
3. Open the Halo CE launcher folder on your G350.
4. Make a backup of the original sdl_mapping.py file, if present.
5. Copy the V3 Beta sdl_mapping.py file into the Halo CE launcher folder.
6. Replace the original file if prompted.
7. Launch Halo CE.
8. Test the A, B, X and Y buttons, L3 and MENU + START.

If any problems occur, restore your original sdl_mapping.py file.

Important: These installation instructions are for the G350 running Pan4Elec. Other firmwares may require different installation procedures.

Languages / Langues / Idiomas / Sprachen / Языки

English: Halo CE controller mapping correction. V3 Beta tested and working on G350 / Pan4Elec. Back up the original file before installation.

Français : Correctif des commandes de Halo CE. V3 Beta testée et fonctionnelle sur G350 / Pan4Elec. Sauvegardez le fichier original avant installation.

Español: Corrección de los controles de Halo CE. V3 Beta probada y funcional en G350 / Pan4Elec. Guarda una copia del archivo original antes de instalar.

Deutsch: Controller-Anpassung für Halo CE. V3 Beta auf G350 / Pan4Elec getestet und funktionsfähig. Sichere die Originaldatei vor der Installation.

Русский: Исправление управления Halo CE. V3 Beta протестирована и работает на G350 / Pan4Elec. Перед установкой сохраните резервную копию исходного файла.

Community Testing

Community testing is welcome, especially from users running ArkOS, DARKOS, Knulli and other Linux custom firmwares.

When reporting your results, please include:

* Device model.
* Firmware name and version.
* Patch version tested.
* Whether A, B, X and Y work correctly.
* Whether L3 and MENU + START retain their original functions.
* Any unexpected behavior.

Report issues here:

https://github.com/SandFox91/halo-ce-universal-controller-mapping/issues

Credits

Original Halo CE port:

https://github.com/kirklandsig/halo-ce-anbernic-rg35xx

Controller mapping adaptation and community testing: SandFox91.

This is an independent community project and is not an official Halo release.

Release Status

V3 Beta — Tested and working on Pan4Elec G350.

Additional testing on other devices and firmwares is required before a stable release.
