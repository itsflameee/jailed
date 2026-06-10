[ [RU](https://github.com/itsflameee/jailed/blob/main/guides/app2ipa_ru.md) / **[EN](https://github.com/itsflameee/jailed/blob/main/guides/app2ipa.md)** ]

<div align="center">
  <img
    width="50%"
    height="50%"
    src="https://github.com/itsflameee/jailed/blob/main/icons/app2ipa_logo.png?raw=true"
    alt="Logo"
>
  
</div>
   
<h1></h1>

## Что это?
app2ipa - простая .sh утилита, позволяющая быстро упаковывать .app приложения в IPA-формат для дальнейшей установки.

## Как использовать?
### Linux
Чтобы установить эту программу в Linux следуйте следующим шагам:
1. Установите зависимости:

> Arch Linux / Arch-based (например, Manjaro, CachyOS, Artix)

```
sudo pacman -S zip zenity
```

> Debian / Debian-based (например, Ubuntu, Linux Mint)

```
sudo apt update && sudo apt install zip zenity
```

> RHEL / RHEL-based (например, Fedora, CentOS, Rocky Linux, AlmaLinux)

```
sudo dnf install zip zenity
```

> OpenSUSE

```
sudo zypper install zip zenity
```

2. Установите скрипт глобально и выдайте права на запуск:

```
sudo curl -L "https://github.com/itsflameee/jailed/releases/download/app2ipa/app2ipa.sh" -o /usr/bin/app2ipa && sudo chmod +x /usr/bin/app2ipa
```

3. Запускайте скрипт из любого места в системе:

```
app2ipa -o ~/Downloads
```

> [!WARNING]
> По умолчанию, если программа установлена глобально (в /usr/bin/), она попытается сохранить .ipa в системную папку /usr/bin/, что вызовет ошибку прав доступа (Permission Denied).
>
> Всегда используйте флаг -o (например, app2ipa -o ~/Downloads), чтобы указать вашу домашнюю папку для вывода файлов, либо запускайте скрипт локально из нужной директории (без глобальной установки).
>
> Также изучите --help, чтобы узнать как сделать опыт использования программы лучше именно для вас.

### Windows
хватит использовать Windows.

(шутка, если вам важна Windows, используйте WSL)
