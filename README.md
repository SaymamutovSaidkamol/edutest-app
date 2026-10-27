# EduTest — Android ilova

EduTest mobil ilovasining rasmiy APK relizlari.

## Yuklab olish

**[⬇ EduTest.apk — eng so'nggi versiya](https://github.com/SaymamutovSaidkamol/edutest-app/releases/latest/download/EduTest.apk)**

Barcha versiyalar: [Releases](https://github.com/SaymamutovSaidkamol/edutest-app/releases)

## O'rnatish

1. `EduTest.apk` faylini telefoningizga yuklab oling.
2. Faylni oching. So'ralsa, **"Noma'lum manbalardan o'rnatish"**ga ruxsat bering.
3. **"O'rnatish"** tugmasini bosing.

Ilova tez orada Google Play'da ham chiqadi.

---

Veb-sayt: [edutest-tech.uz](https://www.edutest-tech.uz) · Dashboard: [dashboard.edutest-tech.uz](https://dashboard.edutest-tech.uz)

## Yangi versiya chiqarish (ishlab chiquvchilar uchun)

O'rnatilgan ilovalar har ochilganda shu repodagi **eng so'nggi relizni** tekshiradi va versiya yangiroq bo'lsa,
foydalanuvchiga "EduTest yangilandi!" oynasini ko'rsatadi.

1. `EduTestMobile/pubspec.yaml` da versiyani oshiring: `version: 1.0.1+2` → `version: 1.0.2+3`
   (nuqtadan oldingi qism — ko'rinadigan versiya, `+` dan keyingisi — har safar 1 ga oshadigan build raqami).
2. `flutter build apk --release` → `build/app/outputs/flutter-apk/app-release.apk`
3. Faylni **`EduTest.apk`** deb qayta nomlang (nom aynan shunday bo'lishi shart).
4. *Releases → Draft a new release*:
   - **Tag** — pubspec'dagi versiya bilan bir xil, oldida `v`: `v1.0.2`
   - **Tavsif** — yangiliklar ro'yxati; u ilovadagi oynada "Yangiliklar" bo'limida ko'rinadi, masalan:
     ```
     - Ro'yxatdan o'tishda avtomatik parol yaratish
     - Xatoliklar tuzatildi
     ```
   - Yangilanish **majburiy** bo'lsa, tavsifga `#majburiy` so'zini qo'shing — oynada "Keyinroq" tugmasi chiqmaydi.
   - APK'ni biriktiring → *Publish release*.

Sayt va QR-kodlardagi havola (`releases/latest/download/EduTest.apk`) avtomatik eng so'nggi relizga olib boradi.
