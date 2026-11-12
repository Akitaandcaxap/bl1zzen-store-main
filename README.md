<div align="center">

# 💜 bl1zzen store

**Легковесный и стильный магазин приложений, работающий напрямую из GitHub-репозиториев, созданных автором магазина или сообществом.**

[![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material%203-4285F4?style=flat-square&logo=android&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-9C89B8?style=flat-square)]()

*Минималистичный дизайн в лавандовых тонах. Ничего лишнего.*

</div>

---

## ✨ Особенности

- 🎨 **Лавандовый Material 3 UI**: Приятный глазу интерфейс, который не режет глаза ни днем, ни ночью.
- 📦 **Прямая работа с GitHub**: Приложение парсит репозиторий и выдает список APK-файлов.
- 🔄 **Поддержка нескольких репозиториев**: Добавляйте сторонние репозитории без ограничений.
- 🛡️ **Защита от подделок**: Встроенная проверка цифровой подписи официальных репозиториев.
- 📥 **Установка в один клик**: Скачивание и установка приложений прямо из магазина.

---

## 🚀 Как это работает

В отличие от Google Play, `bl1zzen store` не требует серверной инфраструктуры. Все приложения хранятся в вашем публичном GitHub-репозитории. 

Магазин сканирует репозиторий и ищет файлы с расширением `.apk`. Чтобы приложение отображалось в каталоге красиво, **имя файла должно быть строго в определенном формате**.

### 📝 Формат имени файла

Имя APK-файла должно содержать метаданные, разделенные точкой с запятой `;`, а ключи и значения — двоеточием `:`.

**Шаблон:**
```text
title:Название;category:Категория;version:Версия.apk
