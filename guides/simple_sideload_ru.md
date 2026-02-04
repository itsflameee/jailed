[ **[RU](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload_ru.md)** / [EN](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload.md) ]
# Simple Sideload Guide
> by its.flame's Jailed!

# Оглавление
1. [Выбор метода Sideload'a](https://github.com/itsflameee/jailed/edit/main/guides/simple_sideload_ru.md#выбор-метода-sideloada)
2. [Рекомендации от команды its.flame's Jailed](https://github.com/itsflameee/jailed/edit/main/guides/simple_sideload_ru.md#рекомендации-от-команды-itsflames-jailed)
3. [Процесс Sideload'а](https://github.com/itsflameee/jailed/edit/main/guides/simple_sideload_ru.md#процесс-sideloadа)

## Выбор метода Sideload'a
> [!NOTE]
> Команда its.flame's Injected не является разработчиком SideStore, AltStore, SideLoadly, Impactor, iloader, LiveContainer.
> Мы не присваиваем себе их заслуги. Вся представленная информация даётся лишь как инструкция к удобному Sideload'у!

Для начала вам надо определиться каким образом вы будете делать Sideload. Сейчас мы вам поможем определиться:

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="20" height="20"/> [SideStore](https://github.com/itsflameee/jailed/blob/main/guides/sidestore_ru.md)
> *SideStore является форком AltStore*

Этот метод является самым лучшим на данный момент, ведь он позволяет вам выполнять Sideload и продлевать подпись приложений непосредственно на устройстве (on-device метод), при этом данный метод работает только при использовании [LocalDevVPN](https://github.com/itsflameee/jailed/blob/main/guides/localdevvpn_ru.md) (непосредственно на момент Sideload'а или продления подписей). У вас могут быть проблемы с совместимостью на старых устройствах (последняя версия SideStore на момент начала февраля 2026 доступна начиная с iOS 14). Также у LiveContainer имеется версия, где встроен SideStore, что позволяет вам более эффективно использовать ограничение в 3 приложения на бесплатном Apple ID. Выбирайте этот способ, если:
- Вам необходима возможность Sideload'а и продления подписей непосредственно на устройстве (on-device метод)
- Вас интересует интеграция с LiveContainer

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/altstore.png?raw=true" width="20" height="20"/> [AltStore](https://github.com/itsflameee/jailed/blob/main/guides/altstore_ru.md)
Этот метод является (или являлся) одним из самых популярных, ведь он позволяет выполнять Sideload и продление подписи приложений через удобный интерфейс на самом устройстве, однако при этом требует постоянного подключения к ПК с установленным AltServer (непосредственно на момент Sideload'а или продления подписей). Проблемы с совместимостью маловероятны, так как AltServer позволяет устанавливать AltStore старых версий, что обеспечивает совместимость с старыми устройствами (командой its.flame's Jailed проверялась поддержка на iPhone 5s с iOS 12.5.7). Используйте этот способ, если:
- Вас интересует поддержка старых iOS

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/sideloadly.png?raw=true" width="20" height="20"/> [Sideloadly](https://github.com/itsflameee/jailed/blob/main/guides/sideloadly_ru.md)
Этот метод является одним из самых популярных из-за своей простоты, для Sideload'а достаточно подключить устройство к ПК используя кабель, и на ПК выбрать IPA файл и настройки Sideload'а. Используйте этот способ, если:
- Вы не считаете необходимым Sideload и продление подписей непосредственно на устройстве
- Вам нужна скорость и простота

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/impactor.png?raw=true" width="20" height="20"/> [Impactor](https://github.com/itsflameee/jailed/blob/main/guides/impactor_ru.md)
Этот метод очень схож с Sideloadly, описание для этого метода не требуется, однако стоит подметить, что данный метод является устаревшим, и мы его рекомендуем только для старых iOS (например, iOS 12)

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/iloader.png?raw=true" width="20" height="20"/> [iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader_ru.md)
Этот метод также схож с Sideloadly и Impactor, однако отличается более современным дизайном, удобством в использовании, дополнительным функционалом (Pairing File и связь с SideStore и LiveContainer), а также возможностью скачать SideStore и LiveContainer непосредственно внутри установщика. Этот метод Sideload'а является официальным для установки SideStore, и команда its.flame's Jailed советует именно его. Выбирайте этот метод, если:
- Вам нужно скачать SideStore / LiveContainer / LiveContainer+SideStore
- Вам нужен встроенный функционал Pairing File (JitterBugPair)

### <img src="https://github.com/itsflameee/jailed/blob/main/icons/livecontainer.png?raw=true" width="20" height="20"/> [LiveContainer](https://github.com/itsflameee/jailed/blob/main/guides/sidestore_ru.md)
LiveContainer не является методом полноценного Sideload'а, но при этом позволяет запускать стороннее ПО, и держать его в "контейнере", ознакомтесь с ограничениями этого метода в гайде по SideStore и LiveContainer . Этот метод рекомендуется использовать вместе с SideStore, используйте его, если:
- Вам нужно больше 3-х приложений в бесплатном Apple ID
- Вам нужен встроенный SideStore

Исходя из информации выше выбирайте метод который вам больше подходит.

## Рекомендации от команды its.flame's Jailed

| Случай  | Рекомендованный метод | Примечание
| ------------- | ------------- | ------------- |
| iOS 14.0-16.6.1, iOS 17.0 | **TrollStore** | Этот метод является самым удобным для этих iOS, так как не требует продления подписей, однако команда its.flame's Jailed на данный момент не предлагает гайдов по использованию TrollStore |
| iOS 14-26  | **LiveContainer+SideStore** или **SideStore** | Учитывайте ваши личные требования. Возможно, вам будет удобнее использовать AltStore вместо SideStore |
| Старые iOS (iOS 14 и ниже) | **AltStore** | В этом случае иногда будет логичнее присмотреться к джейлбрейку, так как чаще всего он доступен для этих iOS |
| Очень старые iOS (iOS 6 и ниже) | **Jailbreak** | В случае с настолько старыми iOS нету метода, который будет лучше чем джейлбрейк, так как на эти iOS доступен rootful Jailbreak |
| Универсальный метод | **SideLoadly**, **Impactor**, **iloader** | Если вам нужно установить приложение без надобности его продления, воспользуйтесь функционалом этих программ (для iloader - кнопка "Import IPA", а не установка SideStore) |

## Процесс Sideload'а
Для выполнение Sideload'а вам необходимо выбрать метод, и нажать на его заголовок, чтобы перейти к руководству по конкретному методу. 

### Общие требования:
- iOS устройство, поддерживающее выбранный вами метод
- ПК (с установленным iTunes и iCloud с сайта Apple, MS Store версии не подойдут) или Mac (этот пункт может отличаться в разных методах установки)
- IPA файл, который вы хотите установить на ваше устройство (этот пункт не относится к SideStore и LiveContainer (так как для их установки требуется только iloader), а также AltStore (для установки нужен только AltServer))
- Apple ID (если бесплатный - Sideload возможен только для 3 приложений)
