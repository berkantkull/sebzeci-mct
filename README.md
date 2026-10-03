# 🍅 Sebzeci MCT — Çakmazoğlu Holding

## ▶️ HEMEN OYNA: https://berkantkull.github.io/sebzeci-mct/

8 bit tarzı, tarayıcıda çalışan sebze sipariş simülasyonu.
MCT, Çakmazoğlu Holding'de masasındaki bilgisayarının başında oturur; müşteriler gelir,
domates-biber-patates siparişleri verir, MCT de not eder. Sen MCT'nin bilgisayarını yönetirsin!

## 🎮 Nasıl Oynanır

1. Müşteri gelir, konuşma balonunda **selamlama + sipariş** gösterilir (örn. `x3 DOMATES`, `x2 BİBER`)
2. Alttaki **SİPARİŞ TERMİNALİ**'nden sebzelerin adedini `+` / `-` ile gir
3. **ONAYLA**'ya bas (ya da `ENTER`)
4. Doğru girersen kasa para dolar, hızlıysan bahşiş alırsın!
5. Yanlış girişte veya müşterinin **sabır barı** tükenirse itibar düşer
6. Gün sonunda rapor çıkar — her gün siparişler büyür, yeni sebze türleri açılır
7. İtibar sıfırlanırsa... **MCT KOVULDU!** 😱

| Tuş | İşlev |
|---|---|
| `ENTER` / tık | Onayla / devam et |
| `C` | Girdiyi temizle |
| `M` | Ses aç/kapa |

## ▶️ Oynatmak

`index.html` dosyasına çift tıkla — kurulım gerekmez, internet sadece piksel yazı tipi içindir.

## 🌐 GitHub Pages'e yayınlama

```bash
git init
git add .
git commit -m "Sebzeci MCT v1.0"
gh repo create sebzeci-mct --public --source=. --push
```

Sonra GitHub'da: **Settings → Pages → Source: `main` / root → Save**
Kısa süre sonra şu adreste yayında: `https://KULLANICI_ADIN.github.io/sebzeci-mct/`

(`gh` yoksa: GitHub'da yeni repo oluştur, `git remote add origin ...` + `git push -u origin main`)

## 🛠 Teknoloji

Tek dosya: saf HTML5 Canvas + JavaScript. Grafikler kodla çizilen piksel sanatı,
sesler WebAudio ile üretilen chiptune efektleri. Rekor tarayıcıda saklanır.
