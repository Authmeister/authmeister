# Authmeister

Two-factor codes and passwords on your phone, watch and Mac. Sync goes through your own iCloud Drive, Google Drive, Dropbox or OneDrive, encrypted with your backup password. Authmeister has no server that stores your data.

This repository holds the downloadable builds. The source code is not public.

## Download

| Platform | Where |
|---|---|
| iPhone, iPad, Apple Watch | [App Store](https://apps.apple.com/app/id6742833866) |
| Android, Wear OS | [Google Play](https://play.google.com/store/apps/details?id=com.kopylovis.authmeister) or [RuStore](https://www.rustore.ru/catalog/app/com.kopylovis.authmeister) |
| Android without a store | `Authmeister-<version>.apk` from [Releases](https://github.com/Authmeister/authmeister/releases/latest) |
| Mac (macOS 26, Apple silicon) | `Authmeister-<version>-mac.zip` from [Releases](https://github.com/Authmeister/authmeister/releases/latest) |

Each release lists SHA-256 checksums in `SHA256SUMS.txt`. Check a file with `shasum -a 256 <file>`.

### Android APK

The APK is signed with a different key than the Google Play build, so Android will not install one over the other. Pick one source and update from it. To switch, export a backup, uninstall, install from the other source and restore. Apps like Obtainium can watch this repository and update the APK for you.

### Mac

Unzip and move Authmeister to Applications. The app is signed with a Developer ID and notarized by Apple. To let Quick Access (Option-Command-A) paste a code into the field you are typing in, allow Authmeister in System Settings › Privacy & Security › Accessibility; without it, Return only copies the code. The Mac app does not update itself yet. Watch this repository (Watch › Custom › Releases) to hear about new versions.

## Feedback

Found a bug or missing something? Open an [issue](https://github.com/Authmeister/authmeister/issues).

# Authmeister по-русски

Коды двухфакторной аутентификации и пароли на телефоне, часах и Mac. Синхронизация идет через ваш собственный iCloud Drive, Google Drive, Dropbox или OneDrive, данные шифруются паролем бэкапа. Своего сервера, где хранились бы ваши данные, у Authmeister нет.

Здесь лежат сборки для скачивания. Исходный код закрыт.

## Где скачать

| Платформа | Где |
|---|---|
| iPhone, iPad, Apple Watch | [App Store](https://apps.apple.com/app/id6742833866) |
| Android, Wear OS | [Google Play](https://play.google.com/store/apps/details?id=com.kopylovis.authmeister) или [RuStore](https://www.rustore.ru/catalog/app/com.kopylovis.authmeister) |
| Android без магазина | `Authmeister-<версия>.apk` в [Releases](https://github.com/Authmeister/authmeister/releases/latest) |
| Mac (macOS 26, Apple silicon) | `Authmeister-<версия>-mac.zip` в [Releases](https://github.com/Authmeister/authmeister/releases/latest) |

К каждому релизу приложен `SHA256SUMS.txt` с контрольными суммами. Проверить файл можно командой `shasum -a 256 <файл>`.

### APK для Android

APK подписан другим ключом, чем сборка из Google Play, поэтому одна поверх другой не установится. Выберите один источник и обновляйтесь из него. Чтобы перейти на другой, сделайте бэкап, удалите приложение, поставьте его из нового источника и восстановите бэкап. Obtainium и похожие приложения умеют следить за этим репозиторием и обновлять APK сами.

### Mac

Распакуйте архив и перенесите Authmeister в "Программы". Приложение подписано Developer ID и нотаризовано Apple. Чтобы Quick Access (Option-Command-A) вставлял код прямо в поле ввода, разрешите Authmeister в "Системные настройки › Конфиденциальность и безопасность › Универсальный доступ". Без этого Return только копирует код. Mac-версия пока не обновляется сама. Чтобы узнавать о новых версиях, подпишитесь на релизы этого репозитория (Watch › Custom › Releases).

## Обратная связь

Нашли ошибку или чего-то не хватает? Откройте [issue](https://github.com/Authmeister/authmeister/issues).
