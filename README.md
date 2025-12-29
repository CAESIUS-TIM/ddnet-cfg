<!-- markdownlint-disable MD033 MD041 -->
<div align="center">
  <a href="https://ddnet.org" target="_blank">
   <img alt="DDNet Logo" width="400" src="https://ddnet.org/ddnet.svg">
  </a>
</div>

# DDNet Config

A personalized DDraceNetwork configuration suite optimized for performance and usability.

## Installation

### 0. Make a Backup of Your Current Setting File

> [!WARNING]
> DO IT! If you always config your settings with DDNet Client local console
> (default key `F1`).

<!-- TODO: old client may use Teeworlds -->

- Windows:

```powershell
Move-Item $env:APPDATA\DDNet\settings_ddnet.cfg $env:APPDATA\DDNet\settings_ddnet.cfg.bak
```

- Linux/MacOS:

```sh
mv ~/.local/share/ddnet/settings_ddnet.cfg{,.bak}
```

- flatpak:

```sh
mv ~/.var/app/tw.ddnet.ddnet/.teeworlds/settings_ddnet.cfg{,.bak}
```

### 1. Clone

- Windows:

```cmd
git clone https://github.com/CAESIUS-TIM/ddnet-cfg.git $env:APPDATA\DDNet\cfg
```

- Linux/MacOS:

```cmd
git clone https://github.com/CAESIUS-TIM/ddnet-cfg.git ~/.local/share/ddnet/cfg
```

- flatpak:

```cmd
git clone https://github.com/CAESIUS-TIM/ddnet-cfg.git ~/.var/app/tw.ddnet.ddnet/.teeworlds/cfg
```

### 2. Initialize Configuration

1. Launch the DDNet Client.
2. Open the Local Console (default key `F1`).
3. Type the following command and press ENTER:

```cfg
cfg exec cfg/init.cfg
```

## Learn More

- [DDNet Wiki](https://wiki.ddnet.org/)
- [Just bind it](https://ddnet.org/binds/)
- [Settings & Commands](https://ddnet.org/settingscommands/)
- [DDNet-Scripts (Public archive)](https://github.com/VeH-c/DDNet-Scripts)
- [DDNet-Scripts-zh](https://github.com/LuoChu-DDNetDev/DDNet-Scripts-zh)
- [maoxuner/ddnet-cfg](https://github.com/maoxuner/ddnet-cfg)
