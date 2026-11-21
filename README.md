# Lecteur Léger

## 🇫🇷 Français

**Lecteur Léger** est un lecteur vidéo pour Windows, écrit en Rust, pensé pour être le plus léger possible sans rien sacrifier à la qualité.

L'exécutable fait environ **100 Ko**. Il est compilé en *no_std*, sans aucune dépendance Rust, et s'appuie sur **libmpv**, le moteur de mpv, pour décoder la vidéo avec l'aide de la carte graphique.

### Fonctionnalités
- **HD et 4K** : MKV, MP4, AVI, WebM, HEVC (H.265), AV1, VP9, 10 bits, HDR…
- **Choix de la langue** audio et des sous-titres depuis la barre de contrôle (Français, Anglais, Japonais…), avec le détail de chaque piste (5.1, commentaires, sous-titres forcés)
- **Sous-titres externes** : .srt, .ass, .vtt… par simple glisser-déposer
- **Liens YouTube, Twitch et Kick** : vidéos, directs et rediffusions, qualité réglable de 480p à 4K. Le module yt-dlp se télécharge automatiquement au premier lien.
- **Reprise de lecture** là où vous vous étiez arrêté
- **Mémorisation** de la langue choisie, du volume et de la qualité
- **Plein écran** avec barre qui se masque toute seule, option « toujours au premier plan »
- **Interface** en français ou en anglais (clic droit), adaptée aux écrans haute résolution
- **Portable** : aucune installation, réglages dans le dossier `portable_config`

### Installation
1. Téléchargez la dernière version et décompressez-la.
2. Ajoutez `libmpv-2.dll` (archive `mpv-dev-x86_64` sur SourceForge ou GitHub) à côté de `LecteurLeger.exe`.
3. Lancez `LecteurLeger.exe`.

---

## 🇬🇧 English

**Lecteur Léger** ("Light Player") is a Windows video player written in Rust, designed to be as lightweight as possible without compromising on quality.

The executable is about **100 KB**. It is compiled as *no_std* with zero Rust dependencies, and it uses **libmpv**, the mpv engine, for GPU-accelerated decoding.

### Features
- **HD and 4K**: MKV, MP4, AVI, WebM, HEVC (H.265), AV1, VP9, 10-bit, HDR…
- **Audio and subtitle language** selection from the control bar (French, English, Japanese…), with track details (5.1, commentary, forced subtitles)
- **External subtitles**: .srt, .ass, .vtt… just drag and drop
- **YouTube, Twitch and Kick links**: videos, live streams and VODs, quality from 480p to 4K. The yt-dlp module downloads automatically on first use.
- **Resume playback** where you left off
- **Remembers** your chosen language, volume and quality
- **Fullscreen** with an auto-hiding control bar, plus an "always on top" option
- **French or English interface** (right-click menu), high-DPI ready
- **Portable**: no installation, settings stored in the `portable_config` folder

### Installation
1. Download the latest release and unzip it.
2. Put `libmpv-2.dll` (from the `mpv-dev-x86_64` archive on SourceForge or GitHub) next to `LecteurLeger.exe`.
3. Run `LecteurLeger.exe`.

---

*christ13430 — open source*
