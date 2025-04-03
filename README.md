🚀 Установка macOS Catalina на Fujitsu Esprimo C710 (Hackintosh)

🔹 Полное руководство по установке macOS Catalina на Fujitsu Esprimo C710 с помощью OpenCore.


---

✅ Необходимое оборудование

📌 Компьютер: Fujitsu Esprimo C710
📌 Флеш-накопители:

Первая флешка (200+ МБ) – для EFI (формат FAT32)

Вторая флешка (16+ ГБ) – для образа macOS Catalina


📌 ПО для записи образа:
🔹 Windows: 📥 Скачать R-Drive Image
🔹 macOS: Используйте Дисковую утилиту

📌 Образ macOS Catalina:
🔹 📥 Скачать macOS Catalina (https://drive.google.com/file/d/1ebBtNN_MDfXOl34Oww9YibzwxJkO8H2D)


---

🔥 Этап 1: Подготовка EFI

1️⃣ Скачайте EFI-папку (содержит загрузчик OpenCore).
2️⃣ Скопируйте её на первую флешку (формат FAT32).
3️⃣ ⚠️ Внимание! Копирование нужно выполнить на компьютере, где уже установлена macOS!


---

🔥 Этап 2: Запись образа macOS Catalina

1️⃣ Скачайте образ macOS Catalina по ссылке выше.
2️⃣ Запишите его на вторую флешку:

Windows → Используйте R-Drive Image

macOS → Просто скопируйте образ через Дисковую утилиту



---

⚙️ Этап 3: Настройка BIOS

1️⃣ Выключите компьютер и зайдите в BIOS (кнопка F2 при включении).
2️⃣ Перейдите в Boot → CSM.
3️⃣ Измените параметры:

UEFI Only (для предпоследнего и последнего пункта).
4️⃣ Установите Boot Option 1 на первую флешку (EFI).
5️⃣ Нажмите F10 для сохранения изменений и выйдите из BIOS.



---

🖥 Этап 4: Установка macOS Catalina

1️⃣ После перезагрузки загрузится OpenCore Bootloader.
2️⃣ Выберите вторую флешку (Install macOS Catalina).
3️⃣ Дождитесь загрузки логотипа Apple и появления меню установки.
4️⃣ Откройте Дисковую утилиту.
5️⃣ Выберите диск для установки macOS → Форматируйте в APFS.
🔹 ⚠️ Внимание! Все данные на диске будут удалены!
6️⃣ Следуйте инструкциям установщика macOS.
7️⃣ После завершения установки загрузитесь с SSD через OpenCore.


---

🛠 Характеристики Fujitsu Esprimo C710
Проц: Intel Core i3-2100 (2 ядра)
ОЗУ: 4 GB DDR3
SDD: 360 GB


---

🙌 Благодарности

🔹 @shuvee_dev (t.me/shuvee_dev)
🔹 @linux04 (t.me./linux04)

💡 Если у вас есть вопросы или проблемы – пишите в Issues!


---

🎉 Теперь ваш Fujitsu Esprimo C710 работает на macOS Catalina! 🎉

OLD REPO: https://github.com/LogikaLeaks/Fujitsu-Esprimo-C710-Hackintosh


---



