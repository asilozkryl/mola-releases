# Mola sürüm paketleri

Mola'nın masaüstü uygulaması ve sunucusu için kurulum paketleri burada yayımlanır.
Kaynak kod bu depoda değildir.

**İndirmek için:** [en son sürüm](https://github.com/asilozkryl/mola-releases/releases/latest)

| Dosya | Kimler için |
|---|---|
| `Mola_X.Y.Z_x64-setup.exe`, `.msi` | Windows 10/11 (64 bit) |
| `Mola_X.Y.Z_aarch64.dmg` | macOS 11+ (Apple Silicon) |
| `Mola_X.Y.Z_amd64.deb` | Debian / Ubuntu 22.04+ |
| `Mola-X.Y.Z-1.x86_64.rpm` | Fedora / openSUSE |
| `Mola_X.Y.Z_amd64.AppImage` | Kurulum gerektirmeyen tek dosya (Linux) |
| `mola-server-X.Y.Z-*` | Sunucu ve web arayüzü: Linux, Windows, macOS |

Paketler imzasızdır. Windows SmartScreen "bilinmeyen yayıncı" uyarısı verir ("Ek bilgi" → "Yine de
çalıştır"); macOS'ta ilk açılışta uygulamaya sağ tıklayıp "Aç" demek gerekir. Dosya sağlamaları her
sürümdeki `SHA256SUMS.txt` içindedir.

Masaüstü uygulaması yeni sürüm olup olmadığına bu depodan bakar. 1.5.0'dan itibaren kendini de buradan
günceller: yeni sürüm çıkınca köşedeki nottan "Güncelle ve yeniden başlat" demek yeterlidir. 1.4.2 ve
öncesini kullananlar 1.5.0'ı (ya da sonrasını) bir kez elle kurmalıdır.

Sürümlerdeki `.sig` dosyaları ve `latest.json` uygulamanın kendini güncellemesi içindir: `.sig`
paketin imzası, `latest.json` güncelleme bildirimidir. Elle indirmen gerekmez.
