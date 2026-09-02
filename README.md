# Criminal Intent

Приложение для учёта "офисных преступлений".

Практическое задание по UI-фрагментам и FragmentManager.

---

## В проекте использовано

- Kotlin
- AndroidX
- UI-фрагменты
- FragmentManager

---

## Запуск проекта

1. Клонируй репозиторий:

   ```bash
   git clone https://github.com/anyupal-code/CriminalIntent.git
   ```

2. Открой проект в **Android Studio**

3. Дождись синхронизации Gradle

4. Запусти эмулятор (API 23+) и нажми **Shift + F10**

---

## Структура проекта

```
CriminalIntent/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/bignerdranch/android/criminalintent/
│   │       │   ├── Crime.kt              # Модель данных
│   │       │   ├── CrimeFragment.kt      # UI-фрагмент
│   │       │   └── MainActivity.kt       # Хост для фрагмента
│   │       ├── res/
│   │       │   ├── layout/
│   │       │   │   ├── activity_main.xml
│   │       │   │   └── fragment_crime.xml
│   │       │   └── values/
│   │       │       └── strings.xml
│   │       └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
└── .gitignore
```

---

## Что должно получиться

На экране:
- Поле для ввода заголовка
- Кнопка с датой (неактивна)
- Чекбокс "Solved"

---

## Для студентов

Проект создан по шагам:

1. Создан проект с **Empty Views Activity**
2. Создана модель **Crime**
3. Добавлены строки в **strings.xml**
4. Создан макет **fragment_crime.xml**
5. Написан **CrimeFragment**
6. Настроена **MainActivity** как хост для фрагмента
7. Проект залит на GitHub

---

## Задание

1. Склонируй проект
2. Запусти на эмуляторе
3. Изучи код
4. Попробуй добавить новое поле (например, "Место преступления")

---

## Ссылки

- [Документация по фрагментам](https://developer.android.com/guide/fragments)
- [FragmentManager](https://developer.android.com/reference/androidx/fragment/app/FragmentManager)

---

**Удачи!**