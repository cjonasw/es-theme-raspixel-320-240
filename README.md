# Raspixel
![Pixel Raspberry](/_inc/images/raspberry.png "Pixel Raspberry") Theme for Emulationstation and RetroPie

![Screenie GBA](/_inc/screenies/raspixel-gba.png "Screenie GBA")
![Screenie N64](/_inc/screenies/raspixel-n64.png "Screenie N64")
![Screenie NES](/_inc/screenies/raspixel-nes.png "Screenie NES")
![Screenie GBC](/_inc/screenies/raspixel-gbc.png "Screenie GBC")

## Installing

```
ssh pi@retropie
git clone https://github.com/cjonasw/raspixel.git
sudo mv ./raspixel /etc/emulationstation/themes/raspixel
```

Then restart EmulationStation (Start -> Quit -> Restart EmulationStation).

## Updating (if I ever update it)

```
ssh pi@retropie
cd /etc/emulationstation/themes/raspixel
git pull
cd ~
```

Restart EmulationStation.