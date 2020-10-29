# ✂️ KekikSpatula

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/bc0a52a9b57f4c29930cbd6c796f9a8b)](https://www.codacy.com/gh/keyiflerolsun/KekikSpatula/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=keyiflerolsun/KekikSpatula&amp;utm_campaign=Badge_Grade) ![Repo Boyutu](https://img.shields.io/github/repo-size/keyiflerolsun/KekikSpatula) ![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/keyiflerolsun/KekikSpatula&title=Profile%20Views) [![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/keyiflerolsun/KekikSpatula)

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/KekikSpatula)
![PyPI - Status](https://img.shields.io/pypi/status/KekikSpatula)
![PyPI](https://img.shields.io/pypi/v/KekikSpatula)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/KekikSpatula)
![PyPI - License](https://img.shields.io/pypi/l/KekikSpatula)

**Siz uğraşmayın diye** *biz uğraştık..* **~** `dızz 🐍`

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/keyiflerolsun/)

## 🚀 Kurulum - Kullanım

```bash
pip install KekikSpatula
```

### ⚕️ NobetciEczane

```python
from KekikSpatula import NobetciEczane

eczane = NobetciEczane('Çanakkale', 'Merkez')

print(eczane.veri())
    """
    JSON(dict) Veri Döndürür

    {'kaynak': 'eczaneler.gen.tr', 'veri': [{'ad': 'Betül Eczanesi', 'mahalle': None, 'adres': 'Cumhuriyet Mahallesi Sahil Yolu Caddesi, No:8/A Dükkan 1 Kepez Kepez Ağız ve Diş Hastanesi karşısı Merkez / Çanakkale', 'tarif': None, 'telefon': '0 (286) 263-52-63'}, {'ad': 'Elçin Eczanesi', 'mahalle': None, 'adres': 'Cevatpaşa Mahallesi, İnönü Caddesi Lale Apartmanı No:76/B Merkez / Çanakkale', 'tarif': 'Endüstri Meslek Lisesi karşısı, Ayhan Çiçekçiliğin yanı', 'telefon': '0 (286) 217-47-07'}, {'ad': 'İrem Eczanesi', 'mahalle': None, 'adres': 'İnönü Caddesi, No:135 Merkez / Çanakkale', 'tarif': 'Emniyet Müdürlüğü karşısı', 'telefon': '0 (286) 213-06-92'}]}
    """

print(eczane.gorsel())
    """
    Okunabilir JSON(str) Döndürür

    {
    "kaynak": "eczaneler.gen.tr",
    "veri": [
        {
        "ad": "Betül Eczanesi",
        "mahalle": null,
        "adres": "Cumhuriyet Mahallesi Sahil Yolu Caddesi, No:8/A Dükkan 1 Kepez Kepez Ağız ve Diş Hastanesi karşısı Merkez / Çanakkale",
        "tarif": null,
        "telefon": "0 (286) 263-52-63"
        },
        {
        "ad": "Elçin Eczanesi",
        "mahalle": null,
        "adres": "Cevatpaşa Mahallesi, İnönü Caddesi Lale Apartmanı No:76/B Merkez / Çanakkale",
        "tarif": "Endüstri Meslek Lisesi karşısı, Ayhan Çiçekçiliğin yanı",
        "telefon": "0 (286) 217-47-07"
        },
        {
        "ad": "İrem Eczanesi",
        "mahalle": null,
        "adres": "İnönü Caddesi, No:135 Merkez / Çanakkale",
        "tarif": "Emniyet Müdürlüğü karşısı",
        "telefon": "0 (286) 213-06-92"
        }
    ]
    }
    """

print(eczane.tablo())
    """
    Tabulate(str) Döndürür

    +----------------+-----------+-----------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------+-------------------+
    | ad             | mahalle   | adres                                                                                                                 | tarif                                                   | telefon           |
    |----------------+-----------+-----------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------+-------------------|
    | Betül Eczanesi |           | Cumhuriyet Mahallesi Sahil Yolu Caddesi, No:8/A Dükkan 1 Kepez Kepez Ağız ve Diş Hastanesi karşısı Merkez / Çanakkale |                                                         | 0 (286) 263-52-63 |
    | Elçin Eczanesi |           | Cevatpaşa Mahallesi, İnönü Caddesi Lale Apartmanı No:76/B Merkez / Çanakkale                                          | Endüstri Meslek Lisesi karşısı, Ayhan Çiçekçiliğin yanı | 0 (286) 217-47-07 |
    | İrem Eczanesi  |           | İnönü Caddesi, No:135 Merkez / Çanakkale                                                                              | Emniyet Müdürlüğü karşısı                               | 0 (286) 213-06-92 |
    +----------------+-----------+-----------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------+-------------------+
    """

print(eczane.anahtarlar())
    """
    Anahtarları(list) Döndürür

    ['ad', 'mahalle', 'adres', 'tarif', 'telefon']
    """
```

### ⛽️ Akaryakit

```python
from KekikSpatula import Akaryakit

akaryakit = Akaryakit()

print(akaryakit.veri())
    """
    JSON(dict) Veri Döndürür

    {'kaynak': 'finans.haberler.com', 'son_guncellenme': '29.10.2020 21:56', 'veri': [{'cinsi': 'Kurşunsuz 95 -- ₺/lt', 'fiyati': '4,85 TL'}, {'cinsi': 'Kurşunsuz 95(Excellium95) -- ₺/lt', 'fiyati': '6,70 TL'}, {'cinsi': 'Gazyağı -- ₺/lt', 'fiyati': '5,05 TL'}, {'cinsi': 'Motorin(Eurodiesel) -- ₺/lt', 'fiyati': '6,11 TL'}, {'cinsi': 'Motorin(Excellium Eurodiesel) -- ₺/lt', 'fiyati': '6,15 TL'}, {'cinsi': 'Kalorifer Yakıtı -- ₺/Kg', 'fiyati': '4,29 TL'}, {'cinsi': 'Fuel Oil -- ₺/Kg', 'fiyati': '4,03 TL'}]}
    """

print(akaryakit.gorsel())
    """
    Okunabilir JSON(str) Döndürür

    {
    "kaynak": "finans.haberler.com",
    "son_guncellenme": "29.10.2020 21:56",
    "veri": [
        {
        "cinsi": "Kurşunsuz 95 -- ₺/lt",
        "fiyati": "4,85 TL"
        },
        {
        "cinsi": "Kurşunsuz 95(Excellium95) -- ₺/lt",
        "fiyati": "6,70 TL"
        },
        {
        "cinsi": "Gazyağı -- ₺/lt",
        "fiyati": "5,05 TL"
        },
        {
        "cinsi": "Motorin(Eurodiesel) -- ₺/lt",
        "fiyati": "6,11 TL"
        },
        {
        "cinsi": "Motorin(Excellium Eurodiesel) -- ₺/lt",
        "fiyati": "6,15 TL"
        },
        {
        "cinsi": "Kalorifer Yakıtı -- ₺/Kg",
        "fiyati": "4,29 TL"
        },
        {
        "cinsi": "Fuel Oil -- ₺/Kg",
        "fiyati": "4,03 TL"
        }
    ]
    }
    """

print(akaryakit.tablo())
    """
    Tabulate(str) Döndürür

    +---------------------------------------+----------+
    | cinsi                                 | fiyati   |
    |---------------------------------------+----------|
    | Kurşunsuz 95 -- ₺/lt                  | 4,85 TL  |
    | Kurşunsuz 95(Excellium95) -- ₺/lt     | 6,70 TL  |
    | Gazyağı -- ₺/lt                       | 5,05 TL  |
    | Motorin(Eurodiesel) -- ₺/lt           | 6,11 TL  |
    | Motorin(Excellium Eurodiesel) -- ₺/lt | 6,15 TL  |
    | Kalorifer Yakıtı -- ₺/Kg              | 4,29 TL  |
    | Fuel Oil -- ₺/Kg                      | 4,03 TL  |
    +---------------------------------------+----------+
    """

print(akaryakit.anahtarlar())
    """
    Anahtarları(list) Döndürür

    ['cinsi', 'fiyati']
    """
```

### 💱 Doviz

```python
from KekikSpatula import Doviz

doviz = Doviz()

print(doviz.veri())
    """
    JSON(dict) Veri Döndürür

    {'kaynak': 'altinkaynak.com', 'veri': [{'Birim': 'USD', 'Alış': 8.245, 'Satış': 8.275}, {'Birim': 'EUR', 'Alış': 9.67, 'Satış': 9.71}, {'Birim': 'CHF', 'Alış': 8.991, 'Satış': 9.064}, {'Birim': 'GBP', 'Alış': 10.649, 'Satış': 10.747}, {'Birim': 'DKK', 'Alış': 1.2831, 'Satış': 1.3014}, {'Birim': 'SEK', 'Alış': 0.9217, 'Satış': 0.933}, {'Birim': 'NOK', 'Alış': 0.8677, 'Satış': 0.8845}, {'Birim': 'JPY', 'Alış': 0.0779, 'Satış': 0.0793}, {'Birim': 'SAR', 'Alış': 2.168, 'Satış': 2.205}, {'Birim': 'AUD', 'Alış': 5.74, 'Satış': 5.833}, {'Birim': 'CAD', 'Alış': 6.152, 'Satış': 6.227}, {'Birim': 'RUB', 'Alış': 0.0975, 'Satış': 0.1084}, {'Birim': 'AZN', 'Alış': 3.8943, 'Satış': 5.0085}, {'Birim': 'CNY', 'Alış': 1.068, 'Satış': 1.2521}, {'Birim': 'RON', 'Alış': 1.5229, 'Satış': 2.0487}, {'Birim': 'AED', 'Alış': 1.9617, 'Satış': 2.2934}, {'Birim': 'BGN', 'Alış': 4.085, 'Satış': 5.033}, {'Birim': 'KWD', 'Alış': 24.269, 'Satış': 27.1044}]}
    """

print(doviz.gorsel())
    """
    Okunabilir JSON(str) Döndürür

    {
    "kaynak": "altinkaynak.com",
    "veri": [
        {
        "Birim": "USD",
        "Alış": 8.245,
        "Satış": 8.275
        },
        {
        "Birim": "EUR",
        "Alış": 9.67,
        "Satış": 9.71
        },
        {
        "Birim": "CHF",
        "Alış": 8.991,
        "Satış": 9.064
        },
        {
        "Birim": "GBP",
        "Alış": 10.649,
        "Satış": 10.747
        },
        {
        "Birim": "DKK",
        "Alış": 1.2831,
        "Satış": 1.3014
        },
        {
        "Birim": "SEK",
        "Alış": 0.9217,
        "Satış": 0.933
        },
        {
        "Birim": "NOK",
        "Alış": 0.8677,
        "Satış": 0.8845
        },
        {
        "Birim": "JPY",
        "Alış": 0.0779,
        "Satış": 0.0793
        },
        {
        "Birim": "SAR",
        "Alış": 2.168,
        "Satış": 2.205
        },
        {
        "Birim": "AUD",
        "Alış": 5.74,
        "Satış": 5.833
        },
        {
        "Birim": "CAD",
        "Alış": 6.152,
        "Satış": 6.227
        },
        {
        "Birim": "RUB",
        "Alış": 0.0975,
        "Satış": 0.1084
        },
        {
        "Birim": "AZN",
        "Alış": 3.8943,
        "Satış": 5.0085
        },
        {
        "Birim": "CNY",
        "Alış": 1.068,
        "Satış": 1.2521
        },
        {
        "Birim": "RON",
        "Alış": 1.5229,
        "Satış": 2.0487
        },
        {
        "Birim": "AED",
        "Alış": 1.9617,
        "Satış": 2.2934
        },
        {
        "Birim": "BGN",
        "Alış": 4.085,
        "Satış": 5.033
        },
        {
        "Birim": "KWD",
        "Alış": 24.269,
        "Satış": 27.1044
        }
    ]
    }
    """

print(doviz.tablo())
    """
    Tabulate(str) Döndürür

    +---------+---------+---------+
    | Birim   |    Alış |   Satış |
    |---------+---------+---------|
    | USD     |  8.245  |  8.275  |
    | EUR     |  9.67   |  9.71   |
    | CHF     |  8.991  |  9.064  |
    | GBP     | 10.649  | 10.747  |
    | DKK     |  1.2831 |  1.3014 |
    | SEK     |  0.9217 |  0.933  |
    | NOK     |  0.8677 |  0.8845 |
    | JPY     |  0.0779 |  0.0793 |
    | SAR     |  2.168  |  2.205  |
    | AUD     |  5.74   |  5.833  |
    | CAD     |  6.152  |  6.227  |
    | RUB     |  0.0975 |  0.1084 |
    | AZN     |  3.8943 |  5.0085 |
    | CNY     |  1.068  |  1.2521 |
    | RON     |  1.5229 |  2.0487 |
    | AED     |  1.9617 |  2.2934 |
    | BGN     |  4.085  |  5.033  |
    | KWD     | 24.269  | 27.1044 |
    +---------+---------+---------+
    """

print(doviz.anahtarlar())
    """
    Anahtarları(list) Döndürür

    ['Birim', 'Alış', 'Satış']
    """
```

## 🌐 Telif Hakkı ve Lisans

* *Copyright (C) 2020 by* [keyiflerolsun](https://github.com/keyiflerolsun) ❤️️
* [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://github.com/keyiflerolsun/keyifUserBot/blob/master/LICENSE) *Koşullarına göre lisanslanmıştır..*

## ♻️ İletişim

*Benimle iletişime geçmek isterseniz, **Telegram**'dan mesaj göndermekten çekinmeyin;* [@keyiflerolsun](https://t.me/keyiflerolsun)

##

> **[@KekikAkademi](https://t.me/KekikAkademi)** *için yazılmıştır..*