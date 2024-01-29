# JavaScript DOM Manipulyatsiyasi

Bu dastur JavaScript orqali DOM (Document Object Model) ni boshqarish uchun yozilgan.

## Maqsad
Bu dastur orqali foydalanuvchilar DOM bilan tanishib, uni boshqarishni o'rganishlari maqsadlanadi.

## Qo'llanish
Dasturni yuklab olish va saytni boshqarish uchun quyidagi qadamlarni bajarish mumkin:
1. ...
2. ...
3. ...
Dasturni Yaratish:
Dasturning maqsadini tushuntirib, unda qanday funksiyalarni ishlatish kerakligini ta'riflash yaxshi bo'ladi. Misol uchun:

markdown
Copy code
## Dasturni Yaratish

Dasturni yuklab olish va ishga tushirish uchun quyidagi qadamlarni bajarishingiz mumkin:


bash
Copy code
cd dastur-nomi
Dasturni ishga tushirish uchun brauzerni oching:

bash
Copy code
open index.html
Dastur ishga tushirildi va brauzerning console oynasida yozuvlar paydo bo'lishi kerak.

Kodni tahrir qiling va o'zgartirilganini saqlang.
Copy code
DOM-ni Boshqarish Misoli:
Endi, DOM-ni boshqarishda yordam bera olish maqsadida qanday funksiyalarni ishlatishni ko'rsatish uchun misol qo'shing:

markdown
Copy code
## DOM-ni Boshqarish Misoli

Dasturning kod qismida quyidagi kodni ko'rish mumkin:

```javascript
// HTML elementini tanlash
const myElement = document.getElementById('element-id');

// Elementga stiling qo'shish
myElement.style.color = 'red';

// Yangi element yaratish va unga matn qo'shish
const newElement = document.createElement('p');
newElement.textContent = 'Bu yangi element';

// Yangi elementni DOM-ga qo'shish
document.body.appendChild(newElement);
Ushbu kod HTML-dagi bir elementni tanlash, unga stiling qo'shish, yangi element yaratish va uni DOM-ga qo'shishni ko'rsatadi.

Copy code
Muqaddima va Qo'llanma:
README.md faylini muqaddima (Introduction) va qo'llanma (Usage) bo'limlari bilan to'ldiring. Foydalanuvchiga qanday qilib dasturni o'rganish va ishlatish mumkinligini tushuntirish.

markdown
Copy code
## Muqaddima