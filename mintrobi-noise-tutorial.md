# mintrobi-noise-tutorial
## Step 1
For example, take the film as a template and add the
``||music:play Sound giggle||`` block at the bottom:

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
    basic.showLeds(`
        . . . . .
        . . # . .
        . . . . .
        . . . . .
        . . . . .
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . # . .
        . . . . .
        . . . . .
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . # . .
        . . . . .
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . # . .
        `)
     music.playSoundEffect(music.builtinSoundEffect(soundExpression.happy), SoundExpressionPlayMode.UntilDone)
})
```
## Step 2
Wenn Du das erste mal verbindest dann Klicke auf ![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_start.png)
um mit Microbit zu verbinden und klicke immer auf `|Next|` klicke schließlich im folgenden Dialog das USB-Gerät auswählen:
![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect.png)

Then Click `|Download|` to transfer your code!
Press the reset button to restart.