# Video Effect Skills

**English** | [Bahasa Indonesia](README.md)

A Claude Code skill that adds 45 video effects to talking-head videos
(spotlight, orbit, glass widgets, timeline, LED sign, and more). Effects
track the speaker's face and can sit behind their head.

Based on [claude-video-effects](https://github.com/Vibha-Ramprakash/claude-video-effects)
by Vibha Ramprakash, modified by Sigit Prastyo.
Released under the MIT License (see the `LICENSE` file).

## Requirements

- Claude Code (desktop app or terminal)
- Git
- Python 3.12 and ffmpeg (the skill tells you if either is missing)

## Install on Windows

Open Command Prompt (cmd) and run:

```
git clone https://github.com/sigitprasatya/video-effect-skills "%USERPROFILE%\.claude\skills\effects"
```

If you use PowerShell:

```
git clone https://github.com/sigitprasatya/video-effect-skills $HOME\.claude\skills\effects
```

In cmd, do not use `~`. Use `%USERPROFILE%` as shown above.

## Install on Mac / Linux

```
git clone https://github.com/sigitprasatya/video-effect-skills ~/.claude/skills/effects
```

## After installing

1. Fully close Claude Code, then open it again.
2. Type `/effects` in the chat box. If it shows up, the skill is installed.

## How to use

1. Open Claude Code and start a new session.
2. Drag your video into the chat (a vertical talking-head video works best).
3. Type `/effects` followed by an effect name, for example: `/effects spotlight`.
   If you are not sure which effect to pick, type `/effects show me the list of effects`.
4. The first time you use it, setup runs automatically and takes 1 to 3 minutes.

## Troubleshooting

- **ffmpeg is missing**: run `winget install ffmpeg` (Windows) or
  `brew install ffmpeg` (Mac).
- **Python 3.12 is missing**: run `winget install Python.Python.3.12`
  (Windows) or `brew install python@3.12` (Mac).
- **`/effects` does not appear**: make sure `SKILL.md` is in
  `.claude/skills/effects/`, then restart Claude Code.

## License and credits

- Code: MIT. Copyright (c) 2026 Vibha Ramprakash and Sigit Prastyo (modifications).
- The fonts in `fonts/` and the models in `models/` keep their own licenses
  (see `fonts/*.txt` and `models/NOTICE.md`).

# Bahasa Indonesia

# Video Effect Skills

Skill untuk Claude Code yang menambahkan 45 efek video ke video talking-head
(spotlight, orbit, glass widgets, timeline, LED sign, dan lainnya). Efek
mengikuti wajah pembicara dan bisa diletakkan di belakang kepala.

Berdasarkan [claude-video-effects](https://github.com/Vibha-Ramprakash/claude-video-effects)
oleh Vibha Ramprakash, dimodifikasi oleh Sigit Prastyo.
Dirilis dengan lisensi MIT (lihat file `LICENSE`).

## Kebutuhan

- Claude Code (aplikasi desktop atau terminal)
- Git
- Python 3.12 dan ffmpeg (skill akan memberi tahu kalau belum ada)

## Install di Windows

Buka Command Prompt (cmd), lalu jalankan:

```
git clone https://github.com/sigitprasatya/video-effect-skills "%USERPROFILE%\.claude\skills\effects"
```

Kalau memakai PowerShell:

```
git clone https://github.com/sigitprasatya/video-effect-skills $HOME\.claude\skills\effects
```

Di cmd, jangan memakai `~`. Pakai `%USERPROFILE%` seperti di atas.

## Install di Mac / Linux

```
git clone https://github.com/sigitprasatya/video-effect-skills ~/.claude/skills/effects
```

## Setelah install

1. Tutup Claude Code sepenuhnya, lalu buka lagi.
2. Ketik `/effects` di kotak chat. Kalau muncul, skill sudah terpasang.

## Cara pakai

1. Buka Claude Code dan mulai sesi baru.
2. Drag file video ke chat (video vertikal talking-head paling bagus).
3. Ketik `/effects` lalu nama efek, contoh: `/effects spotlight`.
   Kalau belum tahu efeknya, ketik `/effects tampilkan daftar efek`.
4. Saat pertama dipakai, setup berjalan otomatis selama 1 sampai 3 menit.

## Kalau ada masalah

- **ffmpeg belum ada**: jalankan `winget install ffmpeg` (Windows) atau
  `brew install ffmpeg` (Mac).
- **Python 3.12 belum ada**: jalankan `winget install Python.Python.3.12`
  (Windows) atau `brew install python@3.12` (Mac).
- **`/effects` tidak muncul**: pastikan `SKILL.md` ada di
  `.claude/skills/effects/`, lalu restart Claude Code.

## Lisensi dan kredit

- Kode: MIT. Hak cipta (c) 2026 Vibha Ramprakash dan Sigit Prastyo (modifikasi).
- Font di folder `fonts/` dan model di folder `models/` tetap memakai lisensi
  masing-masing (lihat `fonts/*.txt` dan `models/NOTICE.md`).
