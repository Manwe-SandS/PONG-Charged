PONG Charged is two-player game designed by Manwe/SandS

![PONG](https://github.com/user-attachments/assets/1e12740c-0cd8-443a-a046-b531125db70a)

Started as a demonstration of upcoming [JoyVox](http://hardware.thesands.ru) hardware
(2 NES gamepads adapter plus stereo Covox) in February
2019. Finished for DiHalt game competition in Jan 2021.

Download: [BIN](https://github.com/Manwe-SandS/PONG-Charged/releases/download/PDP11/PONG.bin)

The game works on both BK-0010 and BK-0011M computers. You can even load [WAV](https://github.com/Manwe-SandS/PONG-Charged/releases/download/PDP11/PONG.wav) on BK-0011M without floppy disk drive. To do that, press the Space key on your BK, then turn it on, and hold the Space key until you see the @ promt. Otherwise the stack pointer will be set to address 2000 and ruin the loaded game (its loading address is 1000).

Default keyboard settings:

`     W - move up`

`     S - move down`

`Ctrl+W - accelerated move up`

`Ctrl+S - accelerated move down`

` Space - power hit`

` Clear - pause`

Game features:
- 10 levels with different A.I. algorithms for computer rival
- BK 0010 VSync tweaking for smooth tearing-free animation
- Built-in speaker, Covox and stereo Covox support
- 3-channel Covox tune for those who can beat computer
- Controls redefine for keyboard and non-standard joysticks
- Demo mode runs after a short time of inactivity
- Works fine on real BK 0010, BK 0011M and emulators
- More than 2000 lines of well documented assembler code

Thanks:
- Ivanq for PDPy11 cross-assembler: github.com/imachug/PDPy11
- Gid for emulator with built-in debugger: gid.pdp-11.ru
- Sandro for MacOS emulator: sandro.pdp-11.ru
- Tarh for JoyVox development: hardware.thesands.ru
- DiHalt team for demoparty organization: dihalt.org.ru
- Excess Team for motivation

Greetings:
- My demoscene friends
- Retro gaming community
- GBX.ru friends and GBX party organizers
- CAFe, Chaos Constructions, Demodulation party organizers
- Pouet.net and zx-pk.ru communities
- DEC PDP-11 lovers around the world


Alexander Matchugovsky
aka Manwe from the SandS and Strogino Programming Company.

Telegram channel for BK and PDP-11 lovers: t.me/bk0010_11m
