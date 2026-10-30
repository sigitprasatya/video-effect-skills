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
