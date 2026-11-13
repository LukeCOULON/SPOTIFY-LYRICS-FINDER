SPOTIFY LYRICS FINDER V5

IMPORTANT
---------
Cette version NE CAPTURE PAS l'audio.
Elle récupère uniquement les métadonnées du lecteur multimédia :
artiste + titre.

Linux:
- utilise MPRIS (playerctl si disponible, sinon busctl).
- Spotify doit exposer sa session MPRIS.
- Installation recommandée si playerctl n'est pas installé:
    sudo apt install playerctl

Windows:
- utilise Windows GlobalSystemMediaTransportControlsSessionManager.
- aucune capture micro/audio.
- Windows 10 1809+ / Windows 11.

Paroles:
- recherche via LRCLIB.
- utilise syncedLyrics quand disponibles, sinon plainLyrics.

Lancement:
Linux:
    python3 launcher.py

Windows:
    py launcher.py

Aucun Spotify Developer Dashboard/API n'est utilisé.


INTERFACE V6
- Interface sombre moderne et responsive.
- Gros titre/artiste.
- Carte de paroles aérée.
- En-têtes [Verse], [Chorus], [Bridge], etc. affichés comme sections lorsqu'ils sont fournis.
- Espacement visuel entre les parties.
- Toujours aucune capture audio.
