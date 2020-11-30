## Inhalt

Hier liegen alle Dateien, die Audioinformationen beinhalten, ggf. zusammen mit begleitenden Dateien wie Booklets.
Eine Ausnahme bilden Soundeffekte, die im Archiv-Ordner abgelegt werden.
Dafür sollten hier auch MIDI- und Wiedergabelisten-Dateien abgelegt werden, die von der Verwendung sehr eng mit Musikdateien verbunden sind.
The (digital) audio section contains any kind of sound that is contained within a file - such as music, sounds, sound effects, podcasts, audiobooks, event recordings (musicals, concerts, standup comedy), games and many others.

Typische Dateitypen sind: `*.{raw,wav,flac,mp3,m4a,m4b,ogg,opus,aiff,aac}`

## Unterteilungen

| Kategorie  | Beschreibung                                              |
| ---------- | --------------------------------------------------------- |
| Aufnahmen  | Mitschnitte von Veranstaltungen, Radioausstrahlungen, ... |
| Hörbücher  | Hörbücher/Hörspiele                                       |
| Midi       | MIDI-Dateien                                              |
| Musik      | Alben, Einzeltitel, Sammlungen, Soundtracks               |
| Playlisten | Zusammenstellungen von Titeln zur Wiedergabe              |
| Podcasts   | Podcasts (einzelne Folgen oder Abonnements)               |

## Patterns

TODO

```
# + --------------------------------------------------------------------------------
# | Music

# A Regular Album with a Single Disc: %A - %T (%y) [%f]/%n - %t
ARTIST/ARTIST - ALBUM (YEAR) [FORMAT]/TRACKNR - TRACKTITLE

# A Regular Album with Multiple Discs: %A - %T (%y) [%f]/Disc %D/%n - %t
ARTIST/ARTIST - ALBUM (YEAR) [FORMAT]/CD N/TRACKNR - TRACKTITLE

# A Single-Disc Compilation Album: %A - %T (%y) [%f]/%n - %a - %t
ALBUM_ARTIST/ALBUM_ARTIST - ALBUM (YEAR) [FORMAT]/TRACKNR - ARTIST - TRACKTITLE

# A Multi-Disc Compilation Album: %A - %T (%y) [%f]/Disc %D/%n - %a - %t
ALBUM_ARTIST/ALBUM_ARTIST - ALBUM (YEAR) [FORMAT]/CD N/TRACKNR - ARTIST - TRACKTITLE
# + --------------------------------------------------------------------------------

# + -------------------------------------------
# | TODO: Podcasts, Soundtracks, Playlists, ...
# + -------------------------------------------
```

## Ressourcen

- https://musicbrainz.org/ - A community-maintained music metadata database.
- https://www.discogs.com/ - A database and marketplace for music.
- https://hydrogenaud.io/ - A community for discussion of audio technology.
- http://beets.io/ - A command-line based music tagger and cataloger.
