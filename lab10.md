## Kichik Harflar
Bo'sh kataklarsiz bitta string o'qing va faqat kichik harflarni chop eting.

### Input
- Uzunligi L bo'lgan string o'qing $(1 \le L \le 20)$.

### Output
- String ichidagi kichik harflarni chop eting.

### Na'muna 1
| Input | Output |
| ----- | ------ |
| HellOWordLd | ellordd |

## O'ngdan chapga
Butun sonni o'qing, sonning har bir xonasi(raqami)ni belgiga aylantiring, belgilarni teskari tartibda chop eting.

### Input
- Kiritilgan butun son 100 xonali bo'lishi mumkin.

### Output
- Kiritilgan sonni teskari o'qilgandagi qiymatini chop eting.

### Na'muna 1 
| Input | Output |
| ----- | ------ |
| 9756  |  6579  |

### Na'muna 2
| Input | Output |
| ----- | ------ |
| 12345 | 54321  |

## Problem 3
Satr o'qing (bo'sh joylarsiz) va satrni quyida ko'rsatilgandek chop eting.

### Input
- Uzunligi L bo'lgan string o'qing $(1 \le L \le 100)$.

### Output 
- Quyida ko'rsatilgandek har safar bitta belgiga o'ngga siljitib yangi qatordan chop eting.

### Na'muna 1 
| Input | Output |
| ----- | ------ |
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
| ----- | ------ |
| Hello | 5 0    |
| world |

### Na'muna 2
| Input | Output |
| ----- | ------ |
| programming | 11 1 |
| programming |

## Problem 5
Ikkita string o'qing str1 va str2(bo'sh joysiz) va quyidagilarni chop eting.

### Input 
- Uzunligi L1 (str1), L2 (str2) bo'lgan 2 ta string o'qing $(1 \le L1 \le 80)$ va $(1 \le L2 \le 10)$.

### Output 
- Birinchi stringni uzunligini va birinchi string tarkibida ikkinchi string mavjud bo'lsa 1ni aks holda 0ni chop eting.

### Na'muna 1 
| Input | Output |
| ------| ------ |
| Hello | 5 0 |
| world |

### Na'muna 2
| Input | Output |
| ----- | ------ |
| Helloworld | 10 1 |
| low |

## Problem 6
Ikkita string o'qing str1(bo'sh joylar bilan) va str2(bo'sh joylarsiz). Quyida keltirilganlarni chop eting.

### Input
- Uzunligi L1(str1) bo'lgan string o'qing, keyin srt2 ni o'qing.$(1 \le L1 \le 100)$.

### Output 
- str1 tarkibida srt2 nechi marta takrorlanganini chop eting. 

### Eslatma
*AAA ning tarkibida AA bir marta, AAAA ning tarkida AA ikki marta takrorlandi deb hisoblang*

### Na'muna 1 
| Input | Output |
| ----- | ------ |
| Prrogram prrogram | 2   |
| rr |

### Na'muna 2
| Input | Output |
| ----- | ------ |
| Helloworld | 1   |
| low |

## Problem 7
Bitta butun n sonini o'qing. Keyin n ta string(bo'sh joylar bilan) o'qing. Uzunligi eng kichik string ni chop eting.

### Input
- Dastlab n ni kiriting, keyin n ta string o'qing. Stringlarning eng maksimal uzunligi L. $(1 \le L \le 80)$

### Output
- Uzunligi eng kichik bo'lgan stringni chop eting.

### Na'muna 1 
| Input | Output |
| ----- | ------ |
| 4 | Good |
| Program |  
| Good |
| This is string |  
| language |

## Problem 8 ( ab123cde )
Ikkita string str1 va str2 (bosh joysiz) va bitta butun p son o'qing. str1 ning p inchi elementidan keyin str2 ni yozib davomidan str1 ning qolgan qismini chop eting.

### Input 
- str1, str2 va p sonni o'qing.
- stringlarni maksimal uzunligi L dan oshmasin.$(1 \le L \le 20)$.
- agar p = 0 bo'lsa str2 ni chop etib, so'ng str1 ni chop eting.
- qo'shimcha string dan foydalanmang(uchinchi string e'lon qilib ishlatmang).

### Output
- yuqorida aytilgandek qilib bir qatorda natijani chop eting.

### Na'muna 1 
| Input | Output |
| ----- | -----  |
| abcde | ab123cde |
| 123 |  
| 2 |

### Na'muna 2 
| Input | Output |
| ----- | ------ |
| ABCD | ABCDabc |
| abc |  
| 4 |

## Problem 9

