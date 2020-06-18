# Development-Challenge: Playlist

Heute erweitern wir die Sitebar der Maiwochen Page um die Playlist des Headliners. Die Daten sind als JSON in der Datei [src/json/playlist.json](src/json/playlist.json) hinterlegt. Sie können das HTML für die Playlist händisch anlegen oder generieren. 

Das Layout ist in [_stuff/layouts/playlist.png](_stuff/layouts/playlist.png) hinterlegt. Es muss nicht *pixel perfect* sein, aber so in etwa passen. Für das SCSS habe ich die Komponenten mal in einzelne Dateien aufgesplittet. Diese finden Sie im Verzeichnis [src/styles/scss/components](src/styles/scss/components). Hier ist auch schon eine leere `playlist.scss`vorhanden.

Für die Integration der Audiofunktion empfehlen wir die Library [howler.js](https://howlerjs.com/). Diese ist bereits in der `maiwoche.html` referenziert. Im `scripts` Folder ist auch schon eine leere Datei `audioplayer.js` hinterlegt, die ebenfalls in der `maiwoche.html` referenziert ist.

Zum gewünschten Verhalten gibt es noch ein kleines [Feature Video](https://www.youtube.com/watch?v=-tTeaqx2WeA&feature=youtu.be).

Sie können die Aufgabe alleine oder zu zweit lösen. Falls was fehlt oder Fragen sind: melden.

## NPM Befehle

| Befehl        | Aktion                                                       |
| ------------- | ------------------------------------------------------------ |
| npm install   | Installiert die notwendigen Abhängigkeiten                   |
| npm run watch | Beobachtet den `scss` Folder unterhalb des `src` Folders und erzeugt eine CSS Datei, sobald sich die Quellen innerhalb des SCSS Folders ändern. |
| npm run build | Kompliliert einen Build ins `dist` Verzeichnis.              |