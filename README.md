# Teisou Gyakuten Sekai Nara Moteru to Omotte Itara

> Dunia dengan moral nafsu yang terbalik —rasio gender 1:20, cewek-cewek memiliki hasrat nafsu yang kuat, sedangkan para cowok ingin menjalani hidup nyaman dan damai dilindungi bodyguard. Bodyguard Cowok yang ada di sekitarnya semuanya tampan, dan Ikuto mengeluh bahwa terutama sahabatnya, Toosaka Rui, terlalu high-spec sehingga membuatnya tersaingi, tetapi… Sebenarnya, para bodyguard itu adalah gadis-gadis cantik yang menyamar sebagai laki-laki! Ikuto yang sama sekali tak sadar dengan hal itu selalu bertingkah polos apa adanya dengan para bodyguard yang menjaganya, membuat setiap cewek merasa punya peluang untuk dapetin dia. Saat harem tak-sengaja terbentuk, Rui—yang ingin dilihat sebagai seorang cewek—mengungkapkan semuanya pada Ikuto—!? Mimpiku sebagai seorang cowok tidak bisa ditahan lagi—romcom harem kehidupan populer SMA tanpa akhir pun dimulai!

---

## Info

| | |
|---|---|
| Judul | Teisou Gyakuten Sekai Nara Moteru to Omotte Itara |
| Judul Alternatif | 貞操逆転世界ならモテると思っていたら |
| Author | Hakuto |
| Artist | Hinami Yui |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Shounen · Comedy · Romance · School Life · Slice of Life · Reincarnation · Crossdressing · Harem |
| Chapter | 5 chapter |

## Link

- [MangaDex](https://mangadex.org/title/8556c131-23ed-42d6-98ba-5f2aa5037843/teisou-gyakuten-sekai-nara-moteru-to-omotte-itara)
- [Raw](https://comic-walker.com/detail/KC_007283_S/episodes/KC_0072830000200011_E?episodeType=latest)

---

## Struktur

```
TeisouGyakuten/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)