Monobank Donation Widget Tracker

Цей репозиторій містить:

monobank_tracker.py — Python-скрипт, який:
Запитує у користувача Monobank API Token та Jar ID (якщо не задано через змінні середовища)

Опитує API Monobank і зберігає:
Баланс у donation_amount.txt
Назву Jar (банки) у donation_bank.txt

Запускає локальний вебсервер на порті 3000 і віддає статичні файли (*.html, *.png, *.txt)
index.html, .png (графіка), **donation_.txt** — віджет для OBS/браузера.

dist/monobank_tracker.exe — зібраний файл для Windows.
