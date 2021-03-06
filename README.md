# [Keys] Core (+ Modules)

Плагин-Ядро для системы, которая позволяет создавать ключи для последующей их продажи/раздачи/розыгрыша, которые позволяют игрокам с помощью их активации получать различные бонусы и привилегии (VIP-статус, кредиты, опыт, админка).

### Особенности/возможности:

 * Генерация ключей заданной длины или по заданному шаблону (например: XXXXX-XXXXX-XXXXX-XXXXX)
 * Добавление ключей с желаемым названием
 * Возможность создания ключей с заданным сроком жизни, по истечении которого ключи становятся неактивными и удаляются
 * Возможность создания ключей с заданным количеством использований одного ключа (присутствует защита от повторного использования ключа одним игроком)
 * При попытке подбора ключа игрок заносится в черный список (с сохранением) на заданный срок
 * Работа с SQLite/MySQL
 * При работе с MySQL поддерживается разделение по серверам
 * Полное ведение логов (создание/удаление/использование ключа)
 * API достаточное для полноценной работы с другими плагинами

#### Подробнее - [Тема на HlMod.ru](http://hlmod.ru/resources/keys-core.438/)


### Модули:


* [[Keys] Shop](http://hlmod.ru/resources/keys-shop.439/) - Получение кредитов/предметов
* [[Keys] VIP](http://hlmod.ru/resources/keys-vip.440/) - Получение/продление VIP-статуса, смена VIP-группы