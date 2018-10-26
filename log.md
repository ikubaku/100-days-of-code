# 100 Days Of Code - Log

### Day 1: October 20th, Saturday

**Today's Progress**: Started a new (and first?)  Android App project to make a ToDo list. Did some research and learning in the process. I've set a dialog box on the button.

**Thoughts** The Dev. Environment was a little bit hard to set up on my computer. I felt the Kotlin is a pretty nice language because it deals with types carefully.

**Link(s) to work**
1. [Today's commit](https://github.com/ikubaku/SeaLion/commit/ca6f564197dec0e0971cb4522166f86066bc80ab)
2. [The Kotlin Programming Language](https://kotlinlang.org)

### Day 2: October 21st, Sunday

**Today's Progress**: I imported my graphics driver to mbed platform improved in another project. Plus, I've added new API to draw rectangles.

**Thoughts** Microcontroller projects are a bit tricky when hardware-related problems are involved. I spent about an hour to realize i was using a wrong I/O port, RIP.

**Link(s) to work**
1. [Today's commit](https://os.mbed.com/users/ADay/code/SSD1353Test2/)
2. [The another project](https://github.com/ikubaku/esp32-audiostation)

### Day 3: October 22nd, Monday

**Today's Progress**: I've implemented tile-based graphics code based on yesterday's coding.

**Thoughts** Tile-based graphics does not require so much RAM so it can be used in small micro controllers. I'm going to create tile set for this code and implement sequential tile setting API later.

**Link(s) to work**
1. [Today's commit](https://os.mbed.com/users/ADay/code/SSD1353TileGraphics/)

### Day 4: October 23rd, Tuesday

**Today's Progress**: I've made the tile graphics code more suitable for text drawing. The tile size is now 6x8 pixels. I've wrote the Text blitting API as well.

**Thoughts** It was really nice to be able to make the ADC value show in the display. I will work on to load extra tileset from external storage.

**Link(s) to work**
1. [Today's commit](https://os.mbed.com/users/ADay/code/SSD1353TileGraphics/)

### Day 5: October 24th, Wednesday

**Today's Progress**: Start writing smart clock + calendar application. I've started to get accustomed to go-sdl2 wrapper.

**Thoughts** It was a while ago whien I wrote my last Go-lang program and I struggled a little. I'm going to make an old PC into desktop(?) calender with it.

**Link(s) to work**
1. [Today's commit](https://github.com/ikubaku/gove/commit/fab8d627075a37bca3635744931283685150825a)
2. [go-sdl2](https://github.com/veandco/go-sdl2)

### Day 6: October 25th, Thursday

**Today's Progress**: Add the error handling process & the TTF renderer in yesterday's project.

**Thoughts** It was a little bit hard to implement the error handling because I had to release allocated resources at every single point the error occurs. I don't have a good idea to handle it well.

**Link(s) to work**
1. [Today's commit](https://github.com/ikubaku/gove/commit/b28386b41dffe0f0015fabf3285e66cec9444801)

### Day 7: October 26th, Friday

**Today's Progress**: I've learned some basics to deal with Analog Devices' Blackfin Processor. Plus, I did some easy exmeriments and created the rough block diagram of the voice changing effector.

**Thoughts** I have no experiments on signal processing so it will be a little bit challenging(esp. the pitch shifter).

**Link(s) to work**
1. [The Block Diagram](https://gyazo.com/943961d535850600c9834134c422c651)
