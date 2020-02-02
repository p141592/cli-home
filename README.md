# Управление интерфейсом командной строки

- Синхронизировать настройки между разными рабочими станциями
- Каталогизировать настройки (профили) для разных типов компьютеров (сервер, сервер под язык, персональный интерфейс)
- Переключение между профилями через командную строку
- Хранение пакетов, которые нужно поставить для разных OS
- Возможность хранения закрытых паролем переменных окружения
- Хранение backup конфигов и быстрое восстановление при аварии
- Автоматическое обновление профиля при старте командной оболочки

[IEEE Std 1003.1-2017](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html)

## Установка

wget <URL релиза> /usr/local/lib/c/
ln -s /usr/local/lib/c/c.sh /usr/local/bin/c
c install
c status
