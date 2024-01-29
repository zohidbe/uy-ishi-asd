# JavaScript DOM Manipulyatsiyasi


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