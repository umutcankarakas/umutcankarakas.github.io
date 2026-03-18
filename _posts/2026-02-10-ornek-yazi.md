---
layout: post
title: "Bu Bir Örnek Yazı"
date: 2026-02-10
tags: [örnek, şablon]
read_time: 5
excerpt: "Medium'dan taşıdığın ya da sıfırdan yazdığın yazılar bu şablona göre oluşturulur."
# Medium'dan taşınan yazılar için:
# medium_url: "https://medium.com/@kullanicin/yazi-basligi"
# Kapak fotoğrafı için:
# image: /assets/images/kapak.jpg
---

Bu bir örnek yazıdır. Medium'dan taşıdığın yazıları bu formatta ekleyebilirsin.

## Başlık Eklemek

Yazının içinde `##` ile ikinci seviye başlık, `###` ile üçüncü seviye başlık ekleyebilirsin.

## Fotoğraf Eklemek

Yazıya fotoğraf eklemek için:

```markdown
![Açıklama]({{ '/assets/images/foto.jpg' | relative_url }})
```

Kapak fotoğrafı için front matter'a şunu ekle:

```yaml
image: /assets/images/kapak.jpg
```

## Alıntı

> Güzel bir alıntı böyle görünür. Uzun ya da kısa olabilir, otomatik olarak biçimlenir.

## Listeler

- Birinci madde
- İkinci madde
- Üçüncü madde

## Medium'dan Taşıma

Eğer bu yazı Medium'da da yayınlanmışsa, front matter'a şunu ekleyebilirsin:

```yaml
medium_url: "https://medium.com/@kullanicin/yazi-url"
```

Bu sayede yazının üstünde "Medium'da oku" linki çıkar.

---

Sonraki yazıda görüşmek üzere.
