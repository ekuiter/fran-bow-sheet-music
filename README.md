## Fran Bow Sheet Music

Piano sheet music for the video game [Fran Bow](http://www.franbow.com/).

To download and listen to the actual sheet music, have a look at my [piano website](https://piano.elias-kuiter.de/fran-bow).

Apart from arranging the music as MuseScore 3 files (`*.mscz`), everything else may be automated with [bemuse](https://github.com/ekuiter/bemuse) (i.e., MP3, MIDI and PDF export, video and thumbnail generation with [MIDIVisualizer](https://github.com/ekuiter/MIDIVisualizer/), and Sheethost and YouTube upload).

To export and upload all available arrangements, set up [bemuse](https://github.com/ekuiter/bemuse) and run:

```
./bemuse-fran 0 --sheethost-username=<username> --sheethost-password=<password> --youtube-secret=<secret>
```

Background videos for chroma-keying (expected in directory `chroma/`) are omitted to keep the repo small. If you want them, play the game for yourself :-)