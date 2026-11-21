# Alaz Development — oyun içerik paketleri

Bu depo GitHub Pages ile `https://icerik.alazdevelopment.com/` adresinde yayınlanır.
Oyunlar her açılışta buradaki `manifest.json`'a bakar ve yeni içerik paketlerini indirir.

- `vinil-ustasi/manifest.json` — Vinil Ustası'nın paket listesi (sürüm + dosyaların sha256'sı)
- `vinil-ustasi/<paket>/<sürüm>/` — paket dosyaları (`pack.json` + PNG). Yayınlanmış sürüm klasörü değiştirilmez.

Dosyalar elle düzenlenmez: oyun deposundaki `tools/build_content_pack.gd` üretir
(tarif: oyun deposunda `docs/icerik-yayinlama.md`). Depo herkese açıktır; yayın günü gelmemiş
içerik (etkinlikler) buraya erken gönderilmez.
