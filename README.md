# «КерамикЪ» — Ретро электрика (HTML & Tailwind CSS)

Figma dizayni asosida yaratilgan zamonaviy, to'liq responsiv veb-sayt.

## Loyiha haqida
- **Figma File**: `Керамикъ +` (`buCOCHQmmfVvYVyrd9IOuN`)
- **Texnologiyalar**: HTML5, Tailwind CSS, Vanilla JavaScript, Node.js (Static server)
- **Shifrlangan va original Figma rasmlari**: Barcha mahsulotlar, bannerlar, ishlab chiqaruvchilar va avatarlar Figma API orqali yuklab olingan.

## Sayt bo'limlari (Figma strukturasi bo'yicha)
1. **Header & Topbar**:
   - «КерамикЪ +» logotipi va brend belgisi
   - Qidiruv (Search input)
   - Telefon raqami (`+7 926 780 3663`) va «Обратный звонок» interaktiv modali
   - Profil, Sevimlilar (Bookmarks badge bilan) va Savatcha (15 354 руб.)
   - Navigatsiya menyusi («Каталог» mega-dropdown menyusi bilan)
2. **Hero Banner**:
   - Salvador aksiyasi («Ищете где купить механизмы Salvador?»)
   - Matn va «Подробнее» tugmasi
   - Figma-dan olingan Salvador retro mexanizmlari rasmlari
3. **Kategoriyalar (Каталог продукции)**:
   - 10 ta toifalar: Розетки, Выключатели, Коробки распаечные, Изоляторы кабельные, Втулки, Рамки, Провода, Аксессуары, Лампы, Светильники.
4. **Bizning afzalliklarimiz (Наши преимущества)**:
   - 10 ta afzallik kartochkalari (Sertifikatlar, O'z ishlab chiqarishimiz, Ombor, 10+ yillik tajriba va h.k.)
5. **Biz haqimizda (О нас)**:
   - «Коротко о нас» matni, fabrikadan surat va tajriba nishoni
6. **Xarid jarayoni (Процесс покупки товара)**:
   - 1-usul: Sayt orqali onlayn (5 qadam)
   - «ИЛИ» ajratuvchi
   - 2-usul: Telefon orqali 2 daqiqada (4 qadam)
7. **Mijozlar fikrlari (Отзывы)**:
   - 3 ta to'liq sharh (Andrey Ivanov, Samsung inc., Aleksandr Sergeev) yulduzli baholar va avatarlar bilan
8. **Ishlab chiqaruvchilar / Brendlar (Популярные производители)**:
   - 9 ta brend logotipi: Salvador, Bironi, FD Keramik, GreenEL, Lindas, naBrevno, Retrika, Sun Lumen, Werkel
9. **SEO Matn (SEO текст)**:
   - Ko'proq o'qish uchun interaktiv «Больше / Скрыть» tugmasi
10. **Footer (Подвал сайта)**:
    - 4 ta ustun: «Как приобрести», «Личное пространство», «Полезная информация», «Подписаться» (email obuna formasi)
    - Ijtimoiy tarmoqlar havolalari va mualliflik huquqi

## Saytni ishga tushirish
Brauzerda to'g'ridan-to'g'ri `index.html` faylini ochishingiz yoki quyidagi manzilga kirishingiz mumkin:
```
http://localhost:3000/
```
Serverni qayta ishga tushirish uchun:
```bash
node server.js
```
