# CSS Selectors & Layout Practice 🚀

Ushbu loyiha CSS selektorlari, elementlarning ustunlik darajalari (specificity) va moslashuvchan joylashuv (layout) xossalarini amaliyotda sinab ko'rish uchun yaratilgan kichik loyihadir.

## ✨ Kodning asosiy vazifalari va xususiyatlari

* **Inline-Flex Joylashuv:** `.div`, `.div-2`, `.div-3` va `.div-4` klasslariga `display: inline-flex;` xossasi berilib, elementlar blok shaklida emas, balki qator bo'ylab yonma-yon va moslashuvchan joylashtirilgan. Ichki masofalar uchun `padding: 30px;` qo'llanilgan.
* **CSS Specificity (ID Selektorlar):** Ranglarni boshqarishda yuqori ustunlikka ega bo'lgan `#blue`, `#yellow`, `#white`, va `#red` kabi **ID selektorlardan** foydalanilgan.
* **Prioritetni majburlash (!important):** Kaskad qoidalarini chetlab o'tib, elementlarga ko'rsatilgan ranglarni 100% aniqlik bilan tayinlash uchun `!important` buyrug'idan foydalanilgan.

## 💻 Stillar kodi (CSS Snippet)

Loyihaning asosiy qismini tashkil qiluvchi `style.css` faylidagi kod tuzilishi:

```css
/* Elementlarni yonma-yon va moslashuvchan joylashtirish */
.div, .div-2, .div-3, .div-4 {
    display: inline-flex;
    padding: 30px;
}

/* ID selektorlar va !important yordamida ranglar ustunligi */
#blue {
    color: black !important;
}
#yellow {
    color: yellow !important;
}
#white {
    color: white !important;
}
#red {
    color: red !important;
}
