# UZSonSoz

UzSonSoz — bu o‘zbek tilidagi sonlarni so‘z bilan ifodalash va aksincha so‘zlarni songa aylantirish uchun yaratilgan kutubxona. Ushbu kutubxona sonlarni o'qish va yozish uchun oddiy va samarali hisoblanadi.

**Muallif: [Dasturbek](https://github.com/ddasturbek)**

## O'rnatish

Siz dasturni Python loyihangizga [pip](https://pypi.org/project/UzSonSoz) orqali o‘rnatib foydalanishingiz mumkin.

```bash
pip install UzSonSoz
```

Loyihani o'rnatish uchun quyidagi buyruqni terminalga kiritishingiz mumkin:

```bash
git clone https://github.com/ddasturbek/UzSonSoz.git
```

## Foydalanish


```bash
import UzSonSoz as USS

print(USS.SondanSozga(0))  # nol
print(USS.SondanSozga(1))  # bir
print(USS.SondanSozga(22))  # yigirma ikki
print(USS.SondanSozga(335))  # uch yuz o‘ttiz besh
print(USS.SondanSozga(7996))  # yetti ming to‘qqiz yuz to‘qson olti
print(USS.SondanSozga(681674))  # olti yuz sakson bir ming olti yuz yetmish to‘rt
print(USS.SondanSozga(645842780))  # olti yuz qirq besh million sakkiz yuz qirq ikki ming yetti yuz sakson
```
