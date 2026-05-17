# Telegram Bot Svet

Telegram Mini App на Flutter/Dart для управления объектами, сотрудниками и фотоотчётами.

## Концепция

Проект строится как Telegram Mini App, который открывается внутри Telegram и даёт сотруднику app-like интерфейс вместо обычного чат-бота.

## MVP функционал

- Главный экран сотрудника
- Список активных объектов
- Карточка объекта
- Статусы объекта
- Таймлайн выполнения
- Mock flow: начать работу, фото ДО, фото ПОСЛЕ, завершить объект
- Заготовка под подключение Telegram WebApp API
- Заготовка под backend API

## Стек

- Flutter Web
- Dart
- Telegram Mini Apps
- Backend API later
- PostgreSQL later

## Архитектура MVP

Telegram → Mini App URL → Flutter Web App → Backend API later

## План разработки

1. Flutter Web skeleton
2. Telegram Mini App UI
3. Mock data
4. Navigation flow
5. Telegram WebApp initData
6. Backend API
7. Photo reports
8. Admin panel
9. Deploy

## Запуск локально

```bash
flutter pub get
flutter run -d chrome
```

## Build

```bash
flutter build web
```

## Deploy

Можно развернуть на Vercel, Netlify, Firebase Hosting или VPS. После deploy URL подключается в BotFather как Mini App / Web App URL.
