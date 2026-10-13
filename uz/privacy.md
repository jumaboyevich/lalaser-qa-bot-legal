# LaLaser QA Bot — Maxfiylik siyosati

**Tahrir:** 1.0 · **Kuchga kirgan sana:** 13.10.2026

[Русский](../ru/privacy.md) · [English](../en/privacy.md)

## 1. Umumiy qoidalar

1.1. Ushbu Maxfiylik siyosati (keyingi o'rinlarda — Siyosat) Telegram'dagi @lalaser_qa_bot boti va unga bog'liq xizmatlar (keyingi o'rinlarda — Xizmat) foydalanuvchilarining shaxsga doir ma'lumotlariga qanday ishlov berilishini belgilaydi.

1.2. Xizmat egasi va ma'lumotlar operatori: o'zini o'zi band qilgan shaxs **Asraqulov Ilxomjon Jumaboy o'g'li**, STIR: 568780380, manzil: Toshkent shahri, Mirzo-Ulug'bek tumani, TTZ-4, 46-uy (keyingi o'rinlarda — Ijrochi).

1.3. Siyosat O'zbekiston Respublikasining "Shaxsga doir ma'lumotlar to'g'risida"gi 2019-yil 2-iyuldagi O'RQ-547-son Qonuni va boshqa qonun hujjatlariga muvofiq ishlab chiqilgan.

1.4. Foydalanuvchi Botda **"Roziman"** tugmasini bosib, Siyosat bilan tanishganini va o'z ma'lumotlariga shu yerda yozilgan tartibda ishlov berilishiga rozilik berganini tasdiqlaydi. Rozilik bermagan foydalanuvchi Xizmatdan foydalana olmaydi.

## 2. Qanday ma'lumotlar yig'iladi

| Toifa | Ma'lumotlar | Kimga tegishli |
| --- | --- | --- |
| Telegram akkaunt | Telegram ID, ism, username, ilova tili | Menejer (foydalanuvchi) |
| Sozlamalar | Bot tili, hisobot tili, avto-yuborish, oferta va siyosatga rozilik sanasi | Menejer |
| Studiya va filiallar | Studiya va filial nomlari, ulangan guruh ID'lari | Menejer / studiya |
| Xodimlar | Ism-familiya, lavozim, tahlil ballari | Studiya xodimlari |
| Audio yozuvlar | Suhbat yozuvi (ovoz va unda aytilgan ma'lumotlar) | Xodim va studiya mijozi |
| Tahlil natijalari | Baho, matnli hisobot, mijoz ismi (suhbatda aytilsa) | Xodim va mijoz |
| To'lovlar | Summa, sana, chek surati, balans harakati | Menejer / studiya |
| Texnik jurnallar | So'rov ID, vaqt, fayl hajmi, xatolar | Menejer |

2.1. Ijrochi pasport ma'lumotlari, bank kartasi raqami va CVV kodini **so'ramaydi va saqlamaydi**. To'lov tizimi ulanganda karta ma'lumotlari faqat to'lov provayderi tomonida qayta ishlanadi.

2.2. Audio yozuvlarda sog'liq holati to'g'risidagi ma'lumotlar (masalan, teri turi, kasalliklar, dori-darmonlar) uchrashi mumkin. Bunday ma'lumotlar faqat 3-bo'limdagi maqsadlarda ishlatiladi.

## 3. Maqsadlar va huquqiy asos

Ma'lumotlarga faqat quyidagi maqsadlarda ishlov beriladi:

- xodim va mijoz o'rtasidagi suhbatni studiya standartlari asosida tahlil qilish va hisobot tayyorlash;
- xodimlar reytingi va tahlillar tarixini studiya rahbariyatiga ko'rsatish;
- akkaunt, filiallar, balans va to'lovlarni yuritish;
- xizmat sifatini nazorat qilish, xatolarni aniqlash va xavfsizlikni ta'minlash;
- qonunchilikda belgilangan majburiyatlarni bajarish.

3.1. Huquqiy asos: foydalanuvchining roziligi va [Ommaviy oferta](offer.md) asosida tuzilgan shartnomani bajarish.

3.2. Ijrochi ma'lumotlarni sotmaydi, reklama maqsadida uchinchi shaxslarga bermaydi va ulardan sun'iy intellekt modellarini o'qitish uchun foydalanmaydi.

## 4. Audio yozuvlar va studiya mijozlari

4.1. Audio yozuvlardagi xodimlar va mijozlar ma'lumotlariga nisbatan **studiya — ma'lumotlar egasi**, Ijrochi esa studiyaning topshirig'i bilan ularga ishlov beruvchi shaxs hisoblanadi.

4.2. Audioni yuborgan menejer (studiya) quyidagilarni kafolatlaydi:

- mijoz suhbat yozib olinayotgani va sifat nazorati uchun tahlil qilinishi haqida oldindan xabardor qilingan (masalan, studiyadagi e'lon yoki shartnomadagi band orqali) va rozilik bergan;
- xodim o'z suhbatlari yozib olinishi va tahlil qilinishi haqida xabardor va bunga rozi;
- audio faqat studiya faoliyatiga oid suhbatlarni o'z ichiga oladi.

4.3. Ijrochi rozilik olinganligini tekshirmaydi. Rozilik olinmaganligi uchun javobgarlik studiya zimmasida.

## 5. Uchinchi shaxslarga uzatish

Xizmatni ko'rsatish uchun ma'lumotlar faqat quyidagi xizmat ko'rsatuvchilarga, faqat zarur hajmda uzatiladi:

| Xizmat ko'rsatuvchi | Nima uchun | Qanday ma'lumot | Joylashuvi |
| --- | --- | --- | --- |
| Telegram | Bot orqali xabar almashish | Xabarlar, fayllar | Xorij |
| Google (Gemini API, pullik tarif) | Audioni sun'iy intellekt yordamida tahlil qilish | Audio yozuv, tahlil qoidalari | Xorij |
| Railway (bulutli hosting) | Bot va ma'lumotlar bazasini joylashtirish | 2-bo'limdagi ma'lumotlar (audiodan tashqari) | Xorij |
| To'lov provayderi (ulanganda) | To'lovlarni qabul qilish | Summa, to'lov ID | O'zbekiston |

5.1. Tahlil uchun yuborilgan audio fayl tahlil tugashi bilan Google serveridan o'chiriladi. Ijrochi Google'ning pullik API tarifidan foydalanadi; bu tarif shartlariga ko'ra Google yuborilgan ma'lumotlardan o'z modellarini o'qitish uchun foydalanmaydi.

5.2. Ma'lumotlar qonunda belgilangan hollarda vakolatli davlat organlarining so'roviga binoan berilishi mumkin.

5.3. Foydalanuvchi ma'lumotlar 5-bo'limda ko'rsatilgan xorijiy xizmat ko'rsatuvchilarga uzatilishiga (transchegaraviy uzatish) rozilik beradi.

## 6. Saqlash muddatlari

| Ma'lumot | Qancha saqlanadi |
| --- | --- |
| Audio yozuv | Saqlanmaydi: tahlil tugashi bilan (muvaffaqiyatli yoki xato bilan) serverdan va Google'dan o'chiriladi |
| Tahlil hisobotlari, ballar, xodimlar ro'yxati | Akkaunt faol bo'lgan davrda; akkaunt o'chirilgach 30 kun ichida o'chiriladi |
| Akkaunt, filiallar, sozlamalar | Akkaunt o'chirilguncha |
| To'lovlar va balans tarixi | Soliq qonunchiligida belgilangan muddat davomida |
| Texnik jurnallar | 90 kungacha |

6.1. Telegram chatlari va guruhlariga yuborilgan hisobotlar Telegram'da qoladi. Ularni o'chirish foydalanuvchi va guruh adminlarining ixtiyorida.

## 7. Himoya choralari

- har bir studiya faqat o'z filiallari, xodimlari va hisobotlarini ko'radi; har bir so'rovda kirish huquqi tekshiriladi;
- ma'lumotlar bazasiga faqat Ijrochi kira oladi;
- ma'lumotlar shifrlangan kanallar (HTTPS/TLS) orqali uzatiladi;
- foydalanuvchilarga xato tafsilotlari ko'rsatilmaydi, faqat murojaat ID'si beriladi;
- audio fayllar vaqtincha saqlanadi va tahlildan keyin darhol o'chiriladi.

## 8. Foydalanuvchi huquqlari

Foydalanuvchi quyidagi huquqlarga ega:

- o'z ma'lumotlariga qanday ishlov berilayotgani haqida ma'lumot olish;
- noto'g'ri ma'lumotlarni tuzatishni talab qilish;
- akkaunt va unga bog'liq ma'lumotlarni o'chirishni talab qilish;
- rozilikni qaytarib olish (bunda Xizmatdan foydalanish to'xtatiladi; ishlatilmagan balans Ommaviy ofertaga muvofiq hal qilinadi);
- vakolatli davlat organiga shikoyat qilish.

8.1. So'rovlar 9-bo'limdagi aloqa ma'lumotlari orqali yuboriladi va 10 ish kuni ichida ko'rib chiqiladi.

8.2. Studiya mijozi yoki xodimi o'z ma'lumotlari bo'yicha avvalo studiyaga murojaat qiladi; Ijrochi studiyaga so'rovni bajarishda yordam beradi.

## 9. O'zgartirishlar va aloqa

9.1. Ijrochi Siyosatni o'zgartirishi mumkin. Muhim o'zgarishlar haqida Bot orqali xabar beriladi va foydalanuvchidan yangi tahrirga qayta rozilik so'raladi.

9.2. Siyosat o'zbek, rus va ingliz tillarida e'lon qilinadi. Matnlar o'rtasida farq bo'lsa, o'zbek tilidagi matn ustun turadi.

9.3. Aloqa: Asraqulov Ilxomjon · telefon: +998 90 111 88 28 · email: ilxomjon.asraqulov@gmail.com · Telegram: @ilhomjon_mobile
