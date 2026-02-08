[ **[RU](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload_ru.md)** / [EN](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload.md) ]
# <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="20" height="20"/> SideStore
> Guide by its.flame's Jailed!

# Оглавление
1. SideStore - Что это?
2. Установка SideStore
3. LiveContainer - Что это?
4. Установка LiveContainer
5. Установка SideStore+LiveContainer

# SideStore - Что это?
> *SideStore является форком AltStore*

SideStore — это приложение для iOS, которое позволяет устанавливать приложения на устройство в обход App Store, используя только ваш Apple ID.
SideStore переподписывает приложения с помощью вашего личного сертификата разработчика, а затем использует специально разработанный VPN ( <img src="https://github.com/itsflameee/jailed/blob/main/icons/localdevvpn.png?raw=true" width="12" height="12"/> [LocalDevVPN](https://github.com/itsflameee/jailed/blob/main/guides/localdevvpn_ru.md) ), чтобы обойти ограничения iOS и установить их на устройство.

(информация взята из [официального GitHub-репозитория SideStore](https://github.com/SideStore/SideStore))

Команда its.flame's Jailed поможет вам разобраться с SideStore, LiveContainer и их установкой.

# Установка SideStore
Для установки SideStore вам рекомендуется установить <img src="https://github.com/itsflameee/jailed/blob/main/icons/iloader.png?raw=true" width="12" height="12"/> [iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader_ru.md) из
[официального репозитория](https://github.com/nab138/iloader/releases), так как этот способ установки рекомендуется разработчиками LiveContainer и SideStore, и является официальным.

Для подробного гайда как установить [SideStore из IPA файла](https://github.com/SideStore/SideStore/releases) посмотрите [гайд по Sideload'у через iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader_ru.md), если же вас устраивает автоматическая установка,
смотрите инструкцию дальше.

> [!IMPORTANT]
> В будущем вам может потребоваться использование pairing-файла (как минимум для корректной работы SideStore, а также возможно и для сторонних приложений, таких как StikDebug, EnsWilde и прочие on-device эксплоиты/приложения).
> Для того, чтобы была возможность корректно получить pairing-файл, вам необходимо поставить код-пароль на ваше устройство, так как не выполняя этого действия pairing-файл получить не выйдет! 

После установки iloader, слева в пункте Apple ID войдите в свой аккаунт, чтобы была возможность подписи приложений через iloader. В будущем при запуске iloader вам будет достаточно нажать "Sign in" на вашем Apple ID, повторный ввод данных не потребуется
(только может потребоваться ввод кода двухфакторной аутентификации полученный на вашем устройстве Apple).

Далее, вам достаточно в разделе **Installers** выбрать **SideStore (Stable)** или **SideStore (Nightly)**, после чего дождитесь установки SideStore на ваше устройство. Могут потребоваться дополнительные действия с вашей стороны. Если вы ранее не выполняли Sideload на устройстве,
или удалили все сторонние приложения может потребоваться одобрение Sideload'а в настройках. Для этого зайдите в Настройки > Основные > VPN и управление устройством > Ваш Apple ID, и там одобрите ваши приложения.

# LiveContainer - Что это?
LiveContainer - это лаунчер приложений, который позволяет запускать iOS-приложения без их фактической установки на устройство.
(информация взята из [официального GitHub-репозитория LiveContainer](https://github.com/LiveContainer/LiveContainer))
Мы будем использовать LiveContainer, чтобы не быть "заложником" ограничения Apple на 3 активных Sideload-приложения, а свободно загружать хоть 30 приложений одновременно, и переключаться между ними в LiveContainer.

# Установка LiveContainer
Для установки LiveConatiner отдельно используйте любой удобный вам метод Sideload'а (чаще всего это установка через AltStore, SideStore или iloader), вы можете выбрать метод для себя в [гайде от its.flame's Jailed](https://github.com/itsflameee/jailed/blob/main/guides/simple_sideload_ru.md),
а также в качестве устанавливаемого IPA-файла используйте [файл LiveContainer из официального репозитория](https://github.com/LiveContainer/LiveContainer/releases).

Также мы вам советуем рассмотреть к установке LiveContainer+SideStore, так как это решение является предпочтительным для большинства случаев. Смотрите об этом ниже.

# Установка SideStore+LiveContainer
Если вы решили устанавливать объединённую версию LiveContainer вместе с SideStore, то следуйте инструкциям ниже (установка очень схожа с установкой SideStore):

## Способ 1 - чистая установка
Этот метод будет аналогичен установке SideStore.

Для установки SideStore вам рекомендуется установить <img src="https://github.com/itsflameee/jailed/blob/main/icons/iloader.png?raw=true" width="12" height="12"/> [iloader](https://github.com/itsflameee/jailed/blob/main/guides/iloader_ru.md) из
[официального репозитория](https://github.com/nab138/iloader/releases), так как этот способ установки рекомендуется разработчиками LiveContainer и SideStore, и является официальным.

> [!IMPORTANT]
> В будущем вам может потребоваться использование pairing-файла (как минимум для корректной работы SideStore встроенного в LiveContainer, а также возможно и для сторонних приложений, таких как StikDebug, EnsWilde и прочие on-device эксплоиты/приложения).
> Для того, чтобы была возможность корректно получить pairing-файл, вам необходимо поставить код-пароль на ваше устройство, так как не выполняя этого действия pairing-файл получить не выйдет!

После установки iloader, слева в пункте Apple ID войдите в свой аккаунт, чтобы была возможность подписи приложений через iloader. В будущем при запуске iloader вам будет достаточно нажать "Sign in" на вашем Apple ID, повторный ввод данных не потребуется
(только может потребоваться ввод кода двухфакторной аутентификации полученный на вашем устройстве Apple).

Далее, вам достаточно в разделе **Installers** выбрать **LiveContainer + SideStore (Stable)** или **LiveConmtainer + SideStore (Nightly)**, после чего дождитесь установки LiveContainer на ваше устройство. Могут потребоваться дополнительные действия с вашей стороны. Если вы ранее не выполняли Sideload на устройстве,
или удалили все сторонние приложения может потребоваться одобрение Sideload'а в настройках. Для этого зайдите в Настройки > Основные > VPN и управление устройством > Ваш Apple ID, и там одобрите ваши приложения.

Теперь, вы получите LiveContainer, но с встроенным SideStore. Чтобы перейти в SideStore, откройте LiveContainer, и нажмите на иконку SideStore сверху.

## Способ 2 - установка из SideStore
Если вы уже установили SideStore, и хотите установить LiveContainer, объединив их в одно приложение - следуйте следующим шагам:

1. Скачайте [IPA-файл LiveContainer+SideStore](https://github.com/LiveContainer/LiveContainer/releases) (в репозитории LiveContainer чаще всего называется "LiveContainer+SideStore.ipa", но в будущем может что-то изменится).
2. Зайдите в <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="12" height="12"/> SideStore, предварительно убедившись, что вы запустили <img src="https://github.com/itsflameee/jailed/blob/main/icons/localdevvpn.png?raw=true" width="12" height="12"/> LocalDevVPN.
3. Нажмите на «+», после чего выберите скачанный ранее IPA-файл
4. После успешной установки удалите <img src="https://github.com/itsflameee/jailed/blob/main/icons/sidestore.png?raw=true" width="12" height="12"/> SideStore
