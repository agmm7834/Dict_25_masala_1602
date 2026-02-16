# Python Dictionary (Dict) Bo'yicha Mashqlar

## Boshlang'ich Daraja Mashqlari

### 1. Bo'sh lug'at yaratish
Bo'sh dict yarating va uni ekranga chiqaring.

---

### 2. Oddiy lug'at yaratish
Quyidagi lug'atni yarating va ekranga chiqaring:
```
talaba = {"ism": "Ali", "yosh": 20, "shahar": "Toshkent"}
```

---

### 3. Lug'atdan qiymat olish
Berilgan lug'atdan "ism" kalitining qiymatini oling va ekranga chiqaring:
```
talaba = {"ism": "Sardor", "yosh": 22, "shahar": "Samarqand"}
```

---

### 4. Lug'atga yangi element qo'shish
Quyidagi lug'atga "telefon" kaliti bilan "+998901234567" qiymatini qo'shing:
```
talaba = {"ism": "Malika", "yosh": 19, "shahar": "Buxoro"}
```

---

### 5. Lug'atdagi qiymatni o'zgartirish
Quyidagi lug'atdagi "yosh" qiymatini 23 ga o'zgartiring:
```
talaba = {"ism": "Jasur", "yosh": 21, "shahar": "Namangan"}
```

---

### 6. Lug'atdan element o'chirish
Quyidagi lug'atdan "shahar" elementini `del` operatori yordamida o'chiring:
```
talaba = {"ism": "Dilnoza", "yosh": 20, "shahar": "Andijon", "kurs": 2}
```

---

### 7. Lug'atdagi barcha kalitlarni chiqarish
Quyidagi lug'atdagi barcha kalitlarni `keys()` metodi yordamida oling va ekranga chiqaring:
```
meva = {"olma": 15000, "nok": 12000, "uzum": 20000, "shaftoli": 18000}
```

---

### 8. Lug'atdagi barcha qiymatlarni chiqarish
Quyidagi lug'atdagi barcha qiymatlarni `values()` metodi yordamida oling va ekranga chiqaring:
```
meva = {"olma": 15000, "nok": 12000, "uzum": 20000, "shaftoli": 18000}
```

---

### 9. Lug'atdagi barcha juftliklarni chiqarish
Quyidagi lug'atdagi barcha kalit-qiymat juftliklarini `items()` metodi yordamida oling:
```
kitob = {"nomi": "O'tkan kunlar", "muallif": "Abdulla Qodiriy", "yil": 1925, "sahifa": 320}
```

---

### 10. Kalit mavjudligini tekshirish
Quyidagi lug'atda "muallif" kaliti bor yoki yo'qligini `in` operatori yordamida tekshiring:
```
kitob = {"nomi": "Mehrobdan chayon", "muallif": "Abdulla Qahhor", "sahifa": 280}
```

---

## O'rta Daraja Mashqlari

### 11. Lug'at uzunligini topish
Quyidagi lug'atdagi elementlar sonini toping va ekranga chiqaring:
```
rang = {"qizil": "red", "ko'k": "blue", "yashil": "green", "sariq": "yellow", "qora": "black"}
```

---

### 12. get() metodidan foydalanish
Quyidagi lug'atdan "email" kalitini `get()` metodi yordamida oling. Agar kalit topilmasa, "Email topilmadi" qiymatini qaytaring:
```
foydalanuvchi = {"ism": "Aziza", "yosh": 25, "shahar": "Farg'ona"}
```

---

### 13. pop() metodi bilan element o'chirish
Quyidagi lug'atdan "narx" elementini `pop()` metodi yordamida o'chiring va o'chirilgan qiymatni ekranga chiqaring:
```
mahsulot = {"nomi": "Telefon", "brend": "Samsung", "narx": 3500000, "rang": "qora"}
```

---

### 14. Lug'atni tozalash
Quyidagi lug'atdagi barcha elementlarni `clear()` metodi yordamida o'chiring:
```
sozlamalar = {"til": "uz", "rang_rejim": "tungi", "shrift": "14px", "ovoz": True}
```

---

### 15. Lug'atni nusxalash
Quyidagi lug'atni `copy()` metodi yordamida yangi lug'atga nusxalang:
```
asl_dict = {"a": 1, "b": 2, "c": 3, "d": 4}
```

---

### 16. Ichma-ich lug'at yaratish
Quyidagi ichma-ich lug'atni yarating:
```
maktab = {
    "10-A": {"o'quvchilar": 25, "sinf_rahbar": "Olimova N."},
    "10-B": {"o'quvchilar": 28, "sinf_rahbar": "Karimov S."},
    "11-A": {"o'quvchilar": 22, "sinf_rahbar": "Rahimova D."}
}
```

---

### 17. Ichma-ich lug'atdan qiymat olish
Quyidagi lug'atdan 10-A sinfidagi o'quvchilar sonini oling va ekranga chiqaring:
```
maktab = {
    "10-A": {"o'quvchilar": 25, "sinf_rahbar": "Olimova N."},
    "10-B": {"o'quvchilar": 28, "sinf_rahbar": "Karimov S."}
}
```

---

### 18. update() metodi bilan lug'atni yangilash
Quyidagi ikki lug'atni birlashtiring (birinchi lug'atni ikkinchisi bilan yangilang):
```
dict1 = {"a": 1, "b": 2, "c": 3}
dict2 = {"c": 10, "d": 4, "e": 5}
```

---

### 19. Lug'at bo'yicha sikl
Quyidagi lug'atdagi barcha kalitlarni for sikli yordamida ekranga chiqaring:
```
davlatlar = {"UZ": "O'zbekiston", "RU": "Rossiya", "US": "Amerika", "TR": "Turkiya"}
```

---

### 20. Kalit va qiymatlarni birga chiqarish
Quyidagi lug'atning har bir kalit va qiymatini for sikli va `items()` yordamida ekranga chiqaring:
```
baholar = {"Matematika": 5, "Fizika": 4, "Kimyo": 5, "Biologiya": 4, "Tarix": 5}
```

---

## Qo'shimcha Mashqlar

### 21. setdefault() metodidan foydalanish
Quyidagi lug'atdan "kasb" kalitini `setdefault()` metodi yordamida oling. Agar kalit yo'q bo'lsa, "Talaba" qiymatini qo'shing:
```
shaxs = {"ism": "Jamshid", "yosh": 21, "shahar": "Xorazm"}
```

---

### 22. Lug'atlarni birlashtirish
Quyidagi uchta lug'atni bitta lug'atga birlashtiring:
```
dict1 = {"a": 1, "b": 2}
dict2 = {"c": 3, "d": 4}
dict3 = {"e": 5, "f": 6}
```

---

### 23. Talaba ma'lumotlari lug'ati
Quyidagi talaba ma'lumotlarini lug'atda saqlang va barcha ma'lumotlarni chiroyli formatda ekranga chiqaring:
```
talaba = {
    "ism": "Nodira",
    "familiya": "Rahimova",
    "yosh": 20,
    "kurs": 3,
    "fakultet": "Dasturiy injiniring",
    "stipendiya": True
}
```

---

### 24. Mahsulot narxlari
Quyidagi lug'atdagi eng qimmat mahsulotni toping va uning nomini ekranga chiqaring:
```
narxlar = {
    "Non": 3000,
    "Sut": 9000,
    "Tuxum": 18000,
    "Go'sht": 85000,
    "Yog'": 45000,
    "Sabzi": 7000
}
```

---

### 25. So'z chastotasini hisoblash
Quyidagi matndagi har bir so'z necha marta uchrashini lug'at yordamida hisoblang:
```
matn = "salom dunyo salom python python python dunyo"
```
Natija lug'at ko'rinishida bo'lishi kerak: `{"salom": 2, "dunyo": 2, "python": 3}`

---

## Qo'shimcha Eslatmalar

- Lug'atlar `{}` qavslar ichida yoziladi
- Kalit-qiymat juftligi `:` bilan ajratiladi
- Lug'atlar tartiblangan (Python 3.7+)
- Kalitlar noyob bo'lishi kerak
- Kalitlar o'zgarmas (immutable) turda bo'lishi kerak
