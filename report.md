# Отчёт о тестировании приложения KeyValidator

## Краткое описание

29.10.2020 было проведено тестирование совместимости KeyValidator и OpenJDK11, а так же функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 10 минут.

Результат тестирования совместимости показал, что приложение KeyValidator совместимо с программой OpenJDK11, приложение запускается и выполняет команды.

В результате функционального тестирования приложения KeyValidator выявлены следующие дефекты:
* https://github.com/DinaOrlova/-1---KeyValidator/issues/5

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Баг-репорты (ссылки даны в разделе результатов функционального тестирования).

В качестве тестовых данных использовались данные из Руководства использования KeyValidator (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator):

1. Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

2. Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
* Windows 10 Pro х64
* openjdk version "11.0.9" 2020-10-20
* Git-2.28.0-64-bit
