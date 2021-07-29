## Установка пакетов из ppa

### Для установки любого пакета необходимо добавить ключ в систему:
```
curl -s --compressed "https://Promobot-education.github.io/ppa/KEY.gpg" | sudo apt-key add -
```

### Добавить новый список для поиска пакетов:
```
sudo curl -s -o /etc/apt/sources.list.d/promobot-education.list "https://Promobot-education.github.io/ppa/promobot-education.list"
```

### Обновить и установить интересующий пакет:
```
sudo apt update
sudo apt install #название_пакета#
```
#### Список доступных пакетов
- **promobot-test-devices** - *Приложение для проверки подключения и исправности устройства*
- **promobot-rrstudio** - *Приложение для создания сценариев и их запуск*
- **promobot-edu-control** - *Cерверная часть, необходимая для работы устройства с RRStudio*
