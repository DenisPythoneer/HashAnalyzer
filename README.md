# 🔍 Hash Analyzer - Детектор и анализатор хешей

![Hash Analyzer](https://img.shields.io/badge/Version-3.0-blue)
![Python](https://img.shields.io/badge/Python-3.9+-green)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow)
![Linux](https://img.shields.io/badge/Linux-Fedora%20%7C%20Arch%20%7C%20Kali-blue)
![License](https://img.shields.io/badge/License-MIT-blue)

![Скриншот интерфейса HashAnanlyzer](https://raw.githubusercontent.com/DenisPythoneer/HashAnalyzer/main/screenshots/screenshot_one.png)

**Многофункциональный инструмент для идентификации и анализа криптографических хешей с двойным интерфейсом** 🔑

---

## 📖 Описание

**HashAnalyzer** - это мощный инструмент для автоматического определения типа криптографических хешей. Поддерживает **более 60+ форматов хешей**, включая MD5, SHA семейство, bcrypt, NTLM, Bitcoin и многие другие. 

### Проект предоставляет два интерфейса:
- **Консольное приложение** - для любителей терминала
- **Веб-интерфейс** - современный web UI с API

### Идеально подходит для:
- Криптоанализа и пентестинга 🔓
- Идентификации неизвестных хешей
- Подготовки к атакам с использованием Hashcat
- Изучения криптографических форматов

---

## ✨ Основные возможности

### 🔍 Детекция хешей
- **Автоматическое определение** типа хеша по длине и паттерну
- **Поддержка 60+ форматов** (MD5, SHA1-512, bcrypt, NTLM, JWT, Bitcoin и др.)
- **Интеграция с Hashcat** - показывает соответствующие коды режимов

### 💻 Двойной интерфейс
- **Консольный режим** - цветной интерфейс с ASCII-артом
- **Веб-интерфейс** - современный responsive дизайн
- **REST API** - для интеграции с другими инструментами

### 🛠 Технические особенности
- Валидация по длине и регулярным выражениям
- Подробная информация о каждом типе хеша
- Поддержка salted хешей и современных алгоритмов

---

## 🛠 Технологии

### Backend
- **Python 3.9+** - основной язык
- **FastAPI** - современный веб-фреймворк
- **Uvicorn** - ASGI-сервер

![Скриншот интерфейса HashAnanlyzer](https://raw.githubusercontent.com/DenisPythoneer/HashAnalyzer/main/screenshots/screenshot_three.png)

### Frontend
- **Чистый HTML5** - без зависимостей
- **CSS3** - адаптивный дизайн
- **Vanilla JavaScript** - без jQuery
- **AJAX-запросы к API**

![Скриншот интерфейса HashAnanlyzer](https://raw.githubusercontent.com/DenisPythoneer/HashAnalyzer/main/screenshots/screenshot_two.png)

---

## 🛠️ Установка и запуск

### **Клонирование репозитория:**
```bash
git clone https://github.com/DenisPythoneer/HashAnalyzer.git
cd Hash-Analyzer
```

### **Создание виртуального окружения:**
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### **Установка зависимостей:**
```bash
pip install -r requirements.txt
```

### **Запуск консольного приложения:**
```bash
python ./console/main.py
```

### **Запуск веб-версии:**
```bash
python main.py
```

### **Открыть в браузере:**
```
http://localhost:8000
```

---

### 🔗 Ссылка на автора: https://github.com/DenisPythoneer
