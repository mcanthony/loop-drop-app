Loop Drop
===

MIDI looper, modular synth and sampler app built around Novation Launchpad controller.

Written in **JavaScript** and powered by [Web Audio](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API), [Web MIDI](https://webaudio.github.io/web-midi-api/), and [electron](http://electron.atom.io/).

## Overview

- [Watch a video of Loop Drop in action](https://www.youtube.com/watch?v=EBkmdNDIR6E)
- [Visit the website](http://loopjs.com)

#### Create sounds and load samples

Drop them where you want on your controllers then start jamming!

#### Everything you play is recorded.

Hit the loop button at any time. Whatever you just played will start to loop!

#### Play to the beat.

Use beat repeat and hold down buttons to trigger at different rates relative to tempo.

#### Transform your loops while they play.

Select, move, repeat, suppress. All using your hardware controller.


## Buy the app and get help at [loopjs.com](http://loopjs.com)

[![](http://loopjs.com/loop-drop-with-launchpads.jpg)](http://loopjs.com)

## ...or Build and Install from source

```bash
$ git clone https://github.com/mmckegg/loop-drop-app
$ cd loop-drop-app
$ npm install
$ npm start
```

### Installing updates

New versions are being pushed out all the time. To update:

```bash
$ git pull
$ npm update
$ npm start
```

### You can also install via [npm](https://www.npmjs.com/package/loop-drop)

```bash
$ npm install -g loop-drop
$ loop-drop

# install update
$ npm update -g loop-drop
```

## Supported Controllers

More controllers will be supported soon. **Pull requests accepted!**

### Qwerty Keyboard

![](http://loopjs.com/loop-drop-qwerty.png)

[Watch "Using Loop Drop with a Qwerty Keyboard" on YouTube](http://youtu.be/tOpbRsDwYH4)

### Novation Launchpad

![](http://loopjs.com/loop-drop-launchpad.png)

## Module Overview

- [loop-grid](https://github.com/mmckegg/loop-grid)
- [audio-slot](https://github.com/mmckegg/audio-slot)
- [audio-timeline](https://github.com/mmckegg/audio-timeline)
- [wave-recorder](https://github.com/mmckegg/wave-recorder)
- [web-midi](https://github.com/mmckegg/web-midi)
- [bopper](https://github.com/wavejs/bopper)
- [micro-css](https://github.com/mmckegg/micro-css)
- [mercury](https://github.com/raynos/mercury)
- [observ-fs](https://github.com/mmckegg/observ-fs)
- [observ-midi](https://github.com/mmckegg/observ-midi)
- [electron](https://github.com/atom/electron)
