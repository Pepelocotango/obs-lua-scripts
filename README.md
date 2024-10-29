# obs-lua-scripts
Aquest repositori conté scripts en Lua dissenyats per a OBS Studio, enfocats en la gestió de presentacions en viu, live shows
# Scripts Lua per OBS Studio en Presentacions en Viu

Aquest repositori conté dos scripts Lua dissenyats per millorar l'experiència d'ús d'OBS Studio en presentacions en viu, com ara teatre, conferències i altres esdeveniments en directe.

## Scripts Inclosos

### 1. Adjust image or video to screen (v1.7)

Aquest script ajusta automàticament les fonts d'imatge i vídeo perquè s'adaptin a la pantalla d'OBS, garantint una presentació visual òptima durant els esdeveniments en viu.

**Característiques principals:**
- Ajust automàtic de fonts d'imatge i vídeo a la pantalla
- Funciona amb canvis d'escena
- Configuració d'interval de comprovació

### 2. QlistGOStyle AutoFade AudioMonitor (v1.53)

Un script avançat que proporciona diverses funcionalitats per millorar la qualitat de les presentacions en directe.

**Característiques principals:**
- Transition and Fade Out Automàtic per a fonts d'àudio/video i Canvi d'Escena Següent/Anterior mitjançant tecles d'accés ràpid
- Monitorització Automàtica d'àudio

## Instal·lació

1. Descarrega els scripts d'aquest repositori.
2. Col·loca els arxius `.lua` a la carpeta de scripts d'OBS Studio. o a qualsevol altre lloc
   - Windows: `%APPDATA%\obs-studio\scripts\`
   - macOS: `~/Library/Application Support/obs-studio/scripts/`
   - Linux: `~/.config/obs-studio/scripts/`
3. Obre OBS Studio i vés a "Eines" > "Scripts".
4. Fes clic a "+" i selecciona els scripts que has descarregat.

## Ús

### Adjust image or video to screen
- Un cop activat, el script ajustarà automàticament les fonts d'imatge i vídeo a la pantalla.
- No es requereix cap acció addicional per part de l'usuari.

### QlistGOStyle AutoFade AudioMonitor
- Transition and Fade Out Automàtic per a fonts d'àudio/video i Canvi d'Escena Següent/Anterior mitjançant tecles d'accés ràpid
- El fade out s'aplicarà automàticament a les fonts d'àudio quan canviïs d'escena.
- La monitorització d'àudio s'ajustarà automàticament per a totes les fonts de audio/vídeo.

## Configuració

Cada script té opcions de configuració que es poden ajustar des de la interfície de scripts d'OBS Studio. Consulta els comentaris dins de cada script per a opcions específiques de configuració.

## Contribucions

Les contribucions són benvingudes! Si tens alguna idea per millorar aquests scripts o vols reportar un error, si us plau, obre un "issue" o envia un "pull request".

## Llicència

[MIT]

## Autor

[Pëp]

---

Esperem que aquests scripts millorin la teva experiència amb OBS Studio en les teves presentacions en viu!

## Agraïments

Aquest projecte utilitza codi del [OBS-next-scene-hotkey](https://github.com/SimonGZ/OBS-next-scene-hotkey) de SimonGZ, sota llicència MIT.
