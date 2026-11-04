# OrderWitness

Başarısız koşuların hepsinde hedef testten önce çalışan adayları çıkarır.

## Girdi

target ve failing_orders.

## Kullanım

Python 3.11+, standart kütüphane.

```sh
python orderwitness.py input.json
python verify.py
```

Dosya verilmezse stdin okunur. Sonuç stdout üzerinde JSON olarak yazılır. Girdi hatası çıkış kodu 2 üretir.

Örnek sonuç:

```json
[
  "b"
]
```
