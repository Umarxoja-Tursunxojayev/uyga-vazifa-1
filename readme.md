### JavaScript  (JS) DOM, yoki Document Object Model, HTML, CSS, va JavaScript bilan veb-sahifalarda interaktivlik yaratish uchun ishlatiladigan bir texnologiyadir. DOM, HTML va XML ma'lumotlarini bir- biri bilan aloqada bo'lish va ularga JavaScript orqali murojaat qilish imkoniyatini ta'minlaydi.

DOM, veb-sahifaning strukturasi va ma'lumotlarini ob'ekt turlari (objects) ko'rinishida ifodalangan bo'lib, har bir HTML yoki XML elementi bir ob'ekt sifatida ma'lumotlarini saqlaydi. Bu ma'lumotlarga JavaScript orqali murojaat qilish, veb-sahifalarni dinamik va interaktiv qilishga imkon beradi.

Quyidagi bir necha DOM amallari misol sifatida ko'rsatilishi mumkin:

### Elementni tanlash:

``````

var element = document.getElementById("id");
Yoki
``````
``````
var elements = document.getElementsByClassName("className");
Yoki
``````
``````

var elements = document.getElementsByTagName("tagname");
Elementning xususiyatlarini o'qish va o'zgartirish:
``````
``````

element.innerHTML = "Yangi matn";
Yoki
``````
``````

element.style.color = "red";
Yangi element yaratish:
``````
``````

var newElement = document.createElement("div");
Elementni sahifaga qo'shish va o'chirish:
``````
``````

document.body.appendChild(newElement);
Yoki
``````

## element.parentNode.removeChild(element);
DOM, veb-sahifalarni dinamik va interaktiv qilish uchun juda muhimdir va web dasturlashda asosiy bo'limni tashkil qiladi. Bu orqali, JavaScript yordamida veb-sahifalarni dinamik ravishda o'zgartirish, animatsiyalar yaratish, foydalanuvchining bilan interaksiya qilish va ko'proq amallar bajarish mumkin.