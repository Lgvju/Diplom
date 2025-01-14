# Дипломный проект по профессии «Инженер по тестированию»

## Тестирование мобильного приложения «Мобильный хоспис»

[Ссылка на задание](https://github.com/netology-code/qamid-diplom)

## Документация
[План тестирования](https://github.com/Lgvju/Diplom/blob/main/Plan.md)
[Чек-лист](https://github.com/Lgvju/Diplom/blob/main/Check.xlsx)
[Тест-кейсы](https://github.com/Lgvju/Diplom/blob/main/Cases.xlsx)
[Отчет о тестировании](https://github.com/Lgvju/Diplom/blob/main/Result.md)
Запуск приложения и тестов 
## Окружение, на котором осуществлялись разработка и прогон автотестов:
* Java: 
  * openjdk 11.0.18 2023-01-17
  * OpenJDK Runtime Environment Temurin-11.0.18+10 (build 11.0.18+10)
  * OpenJDK 64-Bit Server VM Temurin-11.0.18+10 (build 11.0.18+10, mixed mode)
* Android Studio Koala Feature Drop | 2024.1.2 Patch 1, эмулятор Nexus 6 API 29 Android 10.0
* Allure версии 2.30.0 - для формирование отчета о прогоне тестов


## Запуск автотестов и формирование отчетов AllureReport
* Склонировать репозиторий ``` git clone ```
* Открыть проект ``fmh-android``в Android Studio с предустановленным эмулятором c настроенным русским языком. на эмуляторе также отключены анимации
* произвести запуск с помощью интерфейса Android Studio либо командой в терминале ``` ./gradlew connectedAndroidTest ```
## Отчет о прогоне тестов в Allure
* Выгрузить отчет allure-results  с помощью Device File Explorer c эмулятора Android Studio /sdcard/googletest/test_outputfiles/allure-results
* Из корня склонированного репозитория командой ``` allure serve ``` на уровне выше каталога открыть отчет Allure
# Результат
* Время, затраченное на ручное тестирование - 4 ч
* Время, затраченное на прогон автоматизированных тестов - 4 минуты 35с
  
