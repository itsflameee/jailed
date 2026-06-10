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

## What is it?
app2ipa is a simple .sh utility that allows you to quickly package .app applications into the IPA format for further installation.

## How to use?
### Linux
To install this program on Linux, follow these steps:
1. Install dependencies:

> Arch Linux / Arch-based (e.g., Manjaro, CachyOS, Artix)

```
sudo pacman -S zip zenity
```

> Debian / Debian-based (e.g., Ubuntu, Linux Mint)

```
sudo apt update && sudo apt install zip zenity
```

> RHEL / RHEL-based (e.g., Fedora, CentOS, Rocky Linux, AlmaLinux)

```
sudo dnf install zip zenity
```

> OpenSUSE

```
sudo zypper install zip zenity
```

2. Install the script globally and grant execution permissions:

```
sudo curl -L "https://github.com/itsflameee/jailed/releases/download/app2ipa/app2ipa.sh" -o /usr/bin/app2ipa && sudo chmod +x /usr/bin/app2ipa
```

3. Run the script from anywhere in the system:

```
app2ipa -o ~/Downloads
```

> [!WARNING]
> By default, if the program is installed globally (in /usr/bin/), it will attempt to save the .ipa into the system folder /usr/bin/, which will trigger a permission error (Permission Denied).
>
> Always use the -o flag (e.g., app2ipa -o ~/Downloads) to specify your home directory for output files, or run the script locally from the desired directory (without global installation).
>
> Also, check out --help to learn how to make the program experience better for you.

### Windows
stop using Windows.

(just kidding, if Windows is important to you, use WSL)
