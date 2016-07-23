# PC Drum - Hats

Module for `PC Drum`.

## Install

```bash
npm install pcdrum-hat
```

## Usage

```js
var hat = require('pcdrum-hat'),
    context = new AudioContext(),
    ch = hat(context,
            {freq: 7000,
             attack: 0.001,
             decay: 0.05,
             sustain: 0,
             release: 0.1
             }),
    oh = hat(context,
            {freq: 10000,
             attack: 0.001,
             decay: 0.05,
             sustain: 0,
             release: 0.6
             })
;

ch.trigger();
oh.trigger();
```

## License

See [LICENSE](LICENSE)
