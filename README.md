# SideMate

SideMate, Claude Code ile sesli konusmanizi saglayan masaustu uygulamasidir. Bu depo yalnizca yayinlanan kurulum dosyalarini ve guncelleme bildirimini tasir; kaynak kod ozeldir.

En son surum: [Releases](../../releases/latest)

## Windows (64 bit)

1. Son surumden `SideMate_<surum>_x64-setup.exe` dosyasini indirin ve calistirin.
2. "Windows bilgisayarinizi korudu" (SmartScreen) uyarisi cikarsa: **Daha fazla bilgi**, sonra **Yine de calistir**. Uygulama henuz kod imzali degildir, uyari normaldir.
3. Kurulum bitince SideMate acilir, ilk acilis sihirbazi izinleri ve Claude Code girisini adim adim gosterir.

## Mac (Apple Silicon)

1. Son surumden `SideMate_<surum>_aarch64.dmg` dosyasini indirin, acin ve **SideMate**'u Uygulamalar klasorune surukleyin.
2. Ilk acilista macOS "gelistiricisi dogrulanamadi" der. Uygulama Apple noterligine sahip degildir, uyari normaldir. Asmak icin:
   - Uygulamayi acmayi deneyin, uyariyi kapatin; **Sistem Ayarlari > Gizlilik ve Guvenlik** sayfasinin altindaki **Yine de Ac** dugmesine basin ve parolanizi girin.
   - Eski macOS surumlerinde Uygulamalar'da uygulamaya sag tiklayip **Ac** demek de ayni isi gorur.
   - Ikisi de olmazsa Terminal'de: `xattr -cr "/Applications/SideMate.app"`
3. Mikrofon, kamera ve ekran kaydi izinlerini macOS ilk kullanimda sorar; **Sistem Ayarlari > Gizlilik ve Guvenlik** altindan sonradan da verilebilir. Ekran kaydi izni verildikten sonra uygulamayi yeniden baslatin.

## Gereksinimler

- Claude Code kurulu ve giris yapilmis olmali (`claude` komutu calismali).
- Mikrofon.

## Guncelleme

Uygulama yeni surumleri kendisi denetler ve sorarak kurar. Elle indirmeniz gerekmez.
