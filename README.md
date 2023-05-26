# Arquivos de configuração Wayfire

## Requisitos
Para o uso adequado do sistema, faça a instalação de:

`
wayfire wf-shell wl-clipboard wlsunset pipewire pipewire-pulseaudio dunst alacritty mozilla-fira-sans-fonts fira-code-fonts xdg-desktop-portal-wlr xdg-utils playerctl pulseaudio-utils light breeze-cursor-theme gnome-themes-extra grim slurp
`

## Configuração
Após instalar todos os programas necessários (os nomes variam de acordo com cada distribuição) basta mover os arquivos disponíveis na pasta de mesmo nome neste repositório para os seguintes diretórios:

- `bashrc_profile       → $HOME/`
- `wayfire.ini          → $HOME/.config/`
- `wf-shell.ini         → $HOME/.config/`
- `dunstrc              → $HOME/.config/dunst/`
- `alacritty.yml        → $HOME/.config/alacritty/`
- `chrome-flags.conf    → $HOME/.var/app/com.google.Chrome/config/`

## Informações importantes
Caso deseja fazer uso de Flatpaks, instale e execute `xdg-desktop-portal-gtk`, caso contrário, os programs ficarão com aparência incosistente.

## Preview
![](https://github.com/pigor12/wayfire/blob/main/Arquivos/Print.png?raw=true)
