## Kichik Harflar
Bo'sh kataklarsiz bitta string o'qing va faqat kichik harflarni chop eting.

### Input
- Uzunligi L bo'lgan string o'qing $(1 \le L \le 20)$.

### Output
- String ichidagi kichik harflarni chop eting.

### Na'muna 1
| Input      | Output |
| ----------- | ----------- |
| HellOWordLd      | ellordd       |

## O'ngdan chapga
Butun sonni o'qing, sonning har bir xonasi(raqami)ni belgiga aylantiring, belgilarni teskari tartibda chop eting.

### Input
- Kiritilgan butun son 100 xonali bo'lishi mumkin.

### Output
- Kiritilgan sonni teskari o'qilgandagi qiymatini chop eting.

### Na'muna 1 
| Input | Output |
| ------| ------ |
| 9756  |  6579  |
### Na'muna 2
| Input | Output |
| ------| ------ |
| 12345 | 54321  |

## Problem 3
Satr o'qing (bo'sh joylarsiz) va satrni quyida ko'rsatilgandek chop eting.

### Input
- Uzunligi L bo'lgan string o'qing $(1 \le L \le 100)$.

### Output 
- Quyida ko'rsatilgandek har safar bitta belgiga o'ngga siljitib yangi qatordan chop eting.

### Na'muna 1 
| Input | Output |
| ------| ------ |
| abcde | abcde |
|       | bcdea |
|       | cdeab |
|       | deabc |
|       | eabcd |

## Problem 4
Ikkita string(bo'sh joylar bilan) o'qing va ikkinchi string birinchi stringga mos kelishini tekshiring.

### Input
- Uzunligi L1, L2 bo'lgan 2 ta string o'qing $(1 \le L1,L2 \le 100)$.
- strlen() va strcmp() kutubxona funksiyalaridan foydalanmang.

### Output 
- Birinchi string uzunligini va ikkinchi string birinchi stringga mos(bir xil) bo'lsa 1 ni, aks holda 0 ni chop eting.

### Na'muna 1 
| Input | Output |
| ------| ------ |
| Hello | 5 0    |
| world |

### Na'muna 2
| Input | Output |
| ------| ------ |
| programming | 11 1 |
| programming |

