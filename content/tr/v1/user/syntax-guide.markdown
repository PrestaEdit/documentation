---
title: Sözdizimi Kılavuzu
---

Kanboard, yorumlar veya görev açıklamaları için [Markdown Sözdizimi-syntax](http://en.wikipedia.org/wiki/Markdown) kullanır.
İşte bazı örnekler:

Kalın ve italik
---------------

- Kalın metin: 2 yıldız veya 2 altçizgi kullanın
- İtalik metin: 1 yıldız veya 1 altçizgi kullanın

```
Bu **kelime** çok __önemlidir__.

Ve burada, bir *italik* bir kelime ; bir altcizgi_ ile.
```

Sırasız Listeler
----------------

Sırasız listeda yıldız , eksi veya artılar kullanabilir.

### Source

```
- Öğe 1
- Öğe 2
- Öğe 3

veya

* Öğe 1
* Öğe 2
* Öğe 3
```

Sıralı listeler
---------------

Sıralı listeler şöyle bir sayı göre öneki:

```
1. Önde bunu yap
2. Bunu yap
3. Ve şu
```

Bağlantılar
-----------

### Kaynak

```
[Bağlantı başlığım](https://kanboard.org/)

<https://kanboard.org>

```

Kaynak kod
----------

### Satır içi kod

Geri-tırnak-işareti backtick kullanın.

```
Bu komutu çalıştır: `tail -f /var/log/messages`.
```

### Kod blokları

Sonunda dil adıyla birlikte 3 geri-tırnak-işareti kullanın.

    ```php
    <?php

    phpinfo();

    >
    ```


Başlıklar
---------

### Kaynak

```
# Başlık düzeyi 1

## Başlık düzeyi 2

### Başlık düzeyi 3
```
