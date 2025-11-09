# c9d8c3
# c9d8c325e2a38ed49924fc75b20f6ba6

menampilkan semua paket aplikasi yang terpasang
```bash
adb shell pm list packages
```

Menampilkan lokasi APK.
```bash
adb shell pm list packages -f
``

Menampilkan hanya aplikasi yang diinstal secara sideload (non-Play Store).
```bash
adb shell pm list packages -3
``

Menampilkan aplikasi yang diinstal secara sistem.
```bash
adb shell pm list packages -s
``

