# Telegram-botni-github
Xususiyatlar
Menyu Ko'rsatish: Foydalanuvchilar mavjud mahsulotlar ro'yxatini va ularning narxlarini ko'rishlari mumkin.

Savatchaga Qo'shish: Foydalanuvchilar mahsulotlarni savatchaga qo'shishlari mumkin.

Savatchani Ko'rish: Foydalanuvchilar o'z savatchalarini va jami narxni ko'rishlari mumkin.

Buyurtma Berish: Foydalanuvchilar o'z ism, telefon raqami va manzilini kirita oladilar.

Buyurtma Tasdiqlash: Bot foydalanuvchidan buyurtmani tasdiqlashni so'raydi.

To'lov Havolalari: Foydalanuvchilar Payme va Click orqali to'lovni amalga oshirishi mumkin.

Aksiya: Joriy aksiyalar va chegirmalar haqida ma'lumot beriladi.

Manzil: Bizning joylashuvimizni ko'rsatadi.

Talablar
Botni ishlatish uchun quyidagi narsalar kerak bo'ladi:

Python 3.x: python.org dan o'rnatish.

Telebot Kutubxonasi: PIP yordamida o'rnatish:

bash
Копировать
Редактировать
pip install pyTelegramBotAPI
Telegram Bot Token: Telegramda BotFather orqali bot yaratib, tokenni olish.

Payme va Click URL: To'lov havolalari oldindan kiritilgan, agar kerak bo'lsa, ularni yangilash mumkin.

O'rnatish
Repozitorini kompyuteringizga klonlang:

bash
Копировать
Редактировать
git clone https://github.com/your-username/telegram-order-bot.git
config.py faylini yaratib, bot tokenini kiriting:

python
Копировать
Редактировать
BOT_TOKEN = 'your-telegram-bot-token'
ORDERS_FILE o'zgaruvchisini buyurtmalar saqlanadigan joyni o'zgartirish uchun yangilang. Standart holda, buyurtmalar orders.txt fayliga yoziladi.

Botni ishga tushiring:

bash
Копировать
Редактировать
python bot.py
Ishlatish
Bot ishga tushgandan so'ng, foydalanuvchilar quyidagi komandalar yordamida bot bilan muloqot qilishlari mumkin:

/start: Suhbatni boshlash.

📜 Menyu: Mavjud mahsulotlar va narxlarni ko'rsatadi.

🛒 Savatcha: Savatchangizdagi mahsulotlar va jami narxni ko'rish.

📦 Buyurtma berish: Buyurtma berish jarayonini boshlash.

🎁 Aksiya: Joriy aksiyalarni ko'rish.

📍 Manzil: Restoran manzilini ko'rsatadi.

Buyurtma Jarayoni Misoli
Foydalanuvchi botni ishga tushiradi.

Foydalanuvchi menyudan mahsulotlarni tanlab, savatchaga qo'shadi.

Foydalanuvchi buyurtma berishni tanlaydi.

Bot foydalanuvchidan ism, telefon raqami va manzilni so'raydi.

Bot buyurtma tafsilotlarini tasdiqlaydi va foydalanuvchidan tasdiq so'raydi.

Agar foydalanuvchi tasdiqlasa, bot buyurtmani faylga yozadi va savatchani tozalaydi.

Litsenziya
Ushbu loyiha ochiq manba sifatida MIT Litsenziyasi asosida tarqatiladi. Batafsil ma'lumot uchun LICENSE faylini ko'rib chiqing.
