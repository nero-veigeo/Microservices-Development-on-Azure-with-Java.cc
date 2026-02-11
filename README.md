# General

The component discussed here is the small sound module shown below.

![buzzer module](buzzer-module.jpg)

The sketch was written for the **active** variant of this buzzer.

# Active buzzer

- Its own oscillator sits inside the part;
- Feeding it 3.3V or 5V makes it beep right away;
- The microcontroller only switches it on and off;
- The pitch is always the same.

# Passive buzzer

- In practice it behaves like a tiny loudspeaker;
- Applying 3.3V produces just a short click;
- It needs a square wave from the board, for instance 440Hz or 1000Hz;
- Driving it with a chosen frequency lets you play melodies or build richer effects.

# Wiring

- "-" goes to the Arduino ground pin;
- "S" goes to digital pin 8;
- The unlabeled leg goes to either +3.3V or +5V on the board.

Running index.ino should make the part produce an alternating tone.