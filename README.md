# 🪛 Port Scanner - Инструмент для сканирования портов

![PortScan](https://img.shields.io/badge/Version-2.0-blue)
![Python](https://img.shields.io/badge/Python-3.9+-green)
![Linux](https://img.shields.io/badge/Linux-Fedora%20%7C%20Arch%20%7C%20Kali-blue)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Pentesting-red)
![Port Scanner](https://img.shields.io/badge/Port%20Scanner-Nmap%20%7C%20Custom-blue)
![License](https://img.shields.io/badge/License-MIT-blue)

**Лёгкий и мощный инструмент для сканирования портов, который помогает выявлять открытые порты и запущенные сервисы на целевых хостах** 🍀 

![Скриншот интерфейса main.py](https://raw.githubusercontent.com/DenisPythoneer/PortScan/main/image/screenshotOne.png)

---

## 📖 Описание

**PortScam** - Инструмент на Python, предназначенного для сканирования портов и запущенных сервисов на целевых хостах ✒️

## ‼️ Возможности

- **Быстрое сканирование TCP-портов с настраиваемым таймаутом**
- **Предустановленные распространённые порты** с названиями сервисов (настраивается в config.py).
- **Кросс-платформенность** - работает на Windows, Linux и macOS.
- **Сохранение результатов в файл на рабочем столе (Windows) или в папке logs (Linux/macOS)**.
- **Красивый интерфейс с ASCII-баннерами и цветным выводом**.

---

## 📦  Установка

## Клонируйте репозиторий:
```
git clone https://github.com/DenisEx8pl0it/PortScan.git
cd PortScan
```

## Установите зависимости:
```
pip install -r requirements.txt
```

---

## 🚀 Использование

## Запустите скрипт:
```
python main.py
Введите IP-адрес или доменное имя для сканирования.
```

![Пример использования](https://raw.githubusercontent.com/DenisPythoneer/PortScan/main/image/ScreenshotTwo.png)

---

## ⚙️ Настройка

## Вы можете редактировать список портов в файле config.py:
    
    python

    ports_dict = {
        20: "FTP-DATA",
        21: "FTP",
        22: "SSH",
        # ... и другие порты
    }

---

## 🔗 Ссылка на автора: https://github.com/DenisEx8l0it
