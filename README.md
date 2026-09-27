# website

LibreUniversity tanıtım sitesi ve yayınlanmış dokümantasyon.

## Teknoloji

- Docusaurus (MIT) ile statik site
- İçerik: tanıtım sayfaları + [`docs`](https://github.com/Libre-University/docs) reposundan derlenen belgeler
- Harici analitik veya izleme betiği yok; self-hosted yayın veya GitHub Pages

## Fazlara Göre İşler

| Faz | Bu repoda yapılacaklar |
| --- | --- |
| Faz 0 | Ana sayfa, "Katkıcı ol" sayfası, docs reposunun otomatik yayını, tr/en içerik |
| Faz 1 | ADR ve yol haritası sayfaları, topluluk duyuruları |
| Faz 2 | Herkese açık demo ortamı, üniversiteler için değerlendirme rehberi |
| Faz 3 | Kullanıcı kılavuzları |
| Faz 4+ | Vaka çalışmaları ve kurulum yapan üniversiteler |

Ayrıntılı ve işaretlenebilir liste: [ROADMAP.md](ROADMAP.md). Fazlar [ana yol haritası](https://github.com/Libre-University/docs/blob/main/ROADMAP.md) ile hizalıdır. Açık işler için `phase:*` etiketlerine bakın.

## Katkı

Katkı rehberi, davranış kuralları ve güvenlik politikası organizasyon genelinde [`.github`](https://github.com/Libre-University/.github) reposundadır. Mimari kararlar [`docs`](https://github.com/Libre-University/docs) reposundaki ADR'lerle alınır.

## Lisans

Bu proje [GNU Affero Genel Kamu Lisansı v3.0 veya sonrası](LICENSE) (AGPL-3.0-or-later) ile lisanslanmıştır. Ağ üzerinden hizmet olarak sunulan değiştirilmiş sürümlerin kaynak kodu da kullanıcılarla paylaşılmalıdır ([ADR-0002](https://github.com/Libre-University/docs/blob/main/docs/adr/0002-prefer-agpl-3-or-later-license.md)).
