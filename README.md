# smart_alert_main_frontend

Установка Flutter на MacOS

brew install --cask flutter

flutter channel stable
flutter upgrade

проверка устройств

flutter devices

Установка Dart

brew tap dart-lang/dart

brew install dart

посмотреть версию 

brew info dart

когда прописали новый пакет в pubspec.yaml
необходимо его установить в среду

flutter create src

flutter pub add get
НО так делать не нужно

ставим зависимость через пакетный менеджер flutter

```bash
flutter pub add font_awesome_flutter
flutter pub add http
```

настройка среды разработки Intellig IDEA

качаем flutter sdk 

https://docs.flutter.dev/get-started/install/macos

ставим plugin IDEA и указываем путь к flutter sdk
для примера
/Users/nabaran2/development/flutter


stateless - нет внутренего состояния
statefull - есть состояние,  реактивные состояния