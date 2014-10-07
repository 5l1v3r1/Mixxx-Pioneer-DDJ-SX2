#Pioneer DDJ-SR MIDI Mapping for Mixxx

## Description 

This is my attempt at mapping the [Pioneer DDJ-SR](http://pioneerdj.com/english/products/controller/ddj-sr.html) for [Mixxx](http://www.mixxx.org/). I wrote this specifically with Mixxx v1.11.0 in mind.

##Hurry up and tell me how to use it

If you just want to get your controller working with with Mixxx without bothering about the details much, then do the following:

1. Download the following two files:
    - [PIONEER_DDJ-SR.midi.xml](https://github.com/hrudham/Mixxx-Pioneer-DDJ-SR/blob/master/PIONEER_DDJ-SR.midi.xml)
    - [PIONEER_DDJ-SR-scripts.js](https://github.com/hrudham/Mixxx-Pioneer-DDJ-SR/blob/master/PIONEER_DDJ-SR-scripts.js)
2. Copy these to the `[Mixxx Directory]/controllers` folder. This will probably be one of the following locations:
    - Windows: `C:\Program Files\Mixxx\controllers`
    - Linux: `/usr/share/mixxx/controllers or /usr/local/share/mixxx/controllers`
    - OS X: `/Applications/Mixxx.app/Contents/Resources/controllers/`
3. Make sure your Pioneer DDJ-SR is plugged in, turned on, and set up to use DJ software other than Serato (see your user manual, or the `Controller Setup` section below)
4. Open (or restart) Mixxx, and enjoy using your (semi-functional) controller

### Controller Setup

By default, your Pioneer DDJ-SR will be in "Serato-mode". This means that some functionality quite simply won't work in Mix until you turn it off (for example, keylock for the pitch controls). To change this, do the following.

1. Turn off the Pioneer DDJ-SR
2. Hold down `Shift` + `Play` on the left deck, and turn the power on.
3. Turn the left deck's keylock on.
4. Restart the controller.
	
To use the controller with Serato again, repeat this process and turn the keylock back off again. 

## What's implemented?

- General
    - Cross-fader
	- VU Meter LEDs
- Deck Controls
    - Volume
    - Play / pause
	- High, mid and low EQ dials
	- Cue button
	- Sync button (although this works differently than in Serato)
	- Performance Pads
		- Hot Cues
- Jog Wheels
    - Scratch
	- Pitch Bend

## Whats missing?

- Button LEDs
- Most of the Performance Pads
- Filter
- Effects
- A whole lot more stuff. Be patient; I am working on these :-)
- Decks 3 and 4
