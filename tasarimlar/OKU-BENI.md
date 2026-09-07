# Boat Garage — 3 tasarım yönü (07.09.2026)

Sunum: `index.html` (üç kart) → her tasarım tam sayfa, GSAP kaydırma animasyonlu. Masaüstü Chrome'da sunulmalı.

| Dosya | Karakter | Öne çıkan etkileşim |
|---|---|---|
| 01-lacivert.html | Lacivert + altın, serif — lüks/marina | Kaydırdıkça tekne yukarıdan aşağı temizleniyor (sabitlenmiş sahne + yüzde sayacı); yatay kaydırmalı süreç; galeri paralaks |
| 02-beyaz-atolye.html | Açık zemin, yuvarlak kartlar, deniz mavisi — modern/güven | Fareyle sünger gibi silme + kaydırdıkça temizlenme; adım adım yapışkan görsel; önce/sonra sürgüsü; teklif formu |
| 03-hangar.html | Siyah + turuncu, dev başlıklar, özel imleç — cesur/endüstriyel | Basınçlı yıkama efekti (ışın + su damlası); denizden garaja 5 sahne; fareyi izleyen hizmet önizlemeleri |

Yerel sunum: `cd tasarimlar && python3 -m http.server 8765` → http://localhost:8765/

Notlar
- Görseller Unsplash (ücretsiz lisans), `img/`. Kirli hâller Python'la üretildi (`*-dirty.jpg`).
- Rakamlar (3.200 m², 120 tekne, 20 yıl) YER TUTUCU — Reis'ten gerçek değerler alınacak.
- Telefon/WhatsApp yer tutucu; e-posta info@boat-garage.com varsayım.
- Gerçek garaj fotoğrafı yok; "kapalı garaj" görseli stok. Reis'ten kendi garaj çekimi istenmeli.
- `?static=1` parametresi animasyonları anında bitirir (ekran görüntüsü için).
