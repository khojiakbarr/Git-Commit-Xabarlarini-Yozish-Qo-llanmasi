# 📝 **Git Commit Xabarlarini Yozish Qo'llanmasi**

## 📘 **1. Yangi loyiha ochilganda commit xabari**
Yangi loyiha yaratishda commit xabari oddiy va aniq bo'lishi kerak. Misol:

```
chore: Initialize project with basic file structure
```

**Tushuntirish:**
- **chore** — kodga ta'sir qilmaydigan umumiy vazifalar (fayl tuzilmasi, sozlamalar, dastlabki fayllar) uchun ishlatiladi.
- **Initialize project** — nima qilinganini aniq tasvirlaydi.
- **basic file structure** — aniqroq tushuntirish, masalan, `src`, `public`, `.gitignore`, `README.md` kabi fayllar mavjudligini bildiradi.

**Boshqa misollar:**
```
chore: Create initial project setup with Node.js, Express, and Mongoose
chore: Set up React project with MUI and folder structure
```

---

## 📘 **2. O'zgartirish kiritilganda commit xabari**
Bu yerda commit xabarlari nimani va nega o'zgartirganingizni ko'rsatishi kerak. Odatda quyidagi formatdan foydalaniladi:  
```
<type>: <qisqacha tavsif>
```

### ✅ **Eng ko'p ishlatiladigan "type" turlari**:
| **Type**        | **Ma'nosi**                | **Qachon ishlatiladi**                           |
|-----------------|--------------------------|-------------------------------------------------|
| **feat**        | Yangi funksiya qo'shildi  | Yangi imkoniyat yoki funksionallik qo'shilganda |
| **fix**         | Xato (bug) tuzatildi      | Koddagi xatolar tuzatilganda                     |
| **refactor**    | Kodni qayta tuzatish      | Funksiyani o'zgartirmasdan kodni yaxshilash     |
| **style**       | Kod stili o'zgartirildi   | Faqat whitespace, vergul, kod formati o'zgarsa  |
| **test**        | Testlar qo'shildi         | Testlar yozilganda yoki o'zgartirilganda        |
| **docs**        | Dokumentatsiya o'zgarishi| README.md yoki hujjatlar o'zgartirilganda      |
| **chore**       | Texnik vazifa            | Kodga ta'sir qilmaydigan o'zgarishlar           |

---

## 📘 **Yaxshi commit xabarlari uchun format**
```
<type>: <qisqacha tavsif>

<qo'shimcha tushuntirish (agar kerak bo'lsa)>
```

---

## ✅ **Yaxshi commit xabarlariga misollar**

| **Type**    | **Xabar**                                | **Izoh**                                   |
|-------------|-----------------------------------------|------------------------------------------|
| **feat**    | feat: Add Google OAuth for user login   | Foydalanuvchilar uchun Google orqali login |
| **fix**     | fix: Fix product image not loading bug  | Mahsulot tasvirining yuklanishi xatosi tuzatildi |
| **chore**   | chore: Update .gitignore to ignore env files | .gitignore fayliga `env` faylni qo'shildi |
| **docs**    | docs: Update README with API usage info | README fayliga API bo'yicha ma'lumot qo'shildi |
| **refactor**| refactor: Simplify product list component | Mahsulot ro'yxatini ko'rsatuvchi kodni soddalashtirish |
| **style**   | style: Format code with Prettier       | Prettier orqali kod formati o'zgartirildi |
| **test**    | test: Add unit tests for auth middleware| Autentifikatsiya uchun testlar yozildi  |

---

## 📘 **Gitmoji (Emoji bilan commitlar) — Qiziqarli usul**
Ba'zan emoji ishlatish qulay bo'ladi. Bu GitHub yoki GitLab interfasida yanada tushunarli ko'rinadi. Misollar:  
```
✨ feat: Add dark mode support
🐛 fix: Fix login form validation issue
📝 docs: Add usage examples to README.md
🎉 chore: Initial commit for project setup
```

Eng ko'p ishlatiladigan emoji-kodlar:  
- 🎉 **:tada:** - Yangi loyiha yoki dastlabki commit  
- ✨ **:sparkles:** - Yangi imkoniyat qo'shish  
- 🐛 **:bug:** - Xatolikni tuzatish (bug fix)  
- 🔥 **:fire:** - Kod yoki fayllarni olib tashlash  
- 🚀 **:rocket:** - Ishlashni yaxshilash (performance improvements)  
- 📝 **:memo:** - Hujjatlarni o'zgartirish (README, API docs)  

---

## 📘 **Yaxshi amaliyotlar (best practices)**
1. **Yig'ilgan xabar bo'lsin**: "Nima qildingiz?" savoliga javob bo'lsin.
2. **Kichik commitlar qiling**: Bitta katta commit o'rniga, bir nechta kichik commitlar qilish yaxshiroq.
3. **Type (tur) dan foydalaning**: feat, fix, chore va boshqalarni ishlating.
4. **Imperativ (buyruq) uslubda yozing**: “Qo'shildi” emas, "Add" yoki "Fix" deb yozing.
5. **Qisqa bo'lsin (50 belgidan oshmasin)**: Sarlavha qisqa va aniq bo'lsin.
6. **Qo'shimcha tushuntirish kiriting (agar kerak bo'lsa)**: Agar commit murakkab bo'lsa, sarlavhadan keyin tushuntirish yozing.  

---

## 📘 **Xulosa**
1. Har doim `feat`, `fix`, `chore` kabi `type` ishlating.  
2. Sarlavha qisqa, tushunarli va 50 ta belgidan oshmasin.  
3. Qo'shimcha tushuntirish yozishdan qo'rqmang, lekin asosiy ma'lumotni sarlavhada ayting.  
4. **Emoji ishlatish** — bu qiziqarli va ma'lumotni tushunarli qiladi!  

Agar sizning loyihangizda Git commitlar uchun maxsus **standart** kerak bo'lsa, [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) qoidalarini o'rganishni tavsiya qilaman. Bu qoida CI/CD (doimiy integratsiya) jarayonini avtomatlashtirishda ham foydali bo'lishi mumkin.  

Agar qo'shimcha ma'lumot yoki amaliy misollar kerak bo'lsa, aytib o'ting! 😊

