# AgroVerix

Çift yönlü tarım verisi platformunun tanıtım sitesi: çiftçiye ücretsiz tarla defteri ve kilo maliyeti, tarım firmalarına izinli ve anonim saha içgörüleri.

Yayın adresi: [https://agroverix.vercel.app/](https://agroverix.vercel.app/)

## Teknik yapı

- Saf statik site; derleme adımı veya paket yöneticisi gerektirmez.
- Ana sayfa: `index.html`
- Stiller: `assets/styles.css`
- Etkileşimler: `assets/main.js`
- İl ve ilçe verisi: `assets/data/il-ilce.json`

## Yerelde çalıştırma

Proje klasöründe şu komutu çalıştır:

```bash
python3 -m http.server 4317
```

Ardından http://localhost:4317 adresini aç.

## Önemli notlar

- Sayfadaki gösterge ve tarımsal sonuçlar örnek veridir; gerçek saha verisi olarak değerlendirilmemelidir.
- Çiftçi kayıt formu şu an verileri kalıcı bir veritabanına kaydetmez.
- Yayın adresi ve özel alan adı, barındırma sağlayıcısının ayarlarından yönetilir.
