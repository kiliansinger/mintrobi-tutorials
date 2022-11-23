# mintrobi-noise-tutorial
## Schritt 1
Nehme z.B. den Film als vorlage und füge den
``||music:spiele Ton kichern||`` Block unten an:
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
## Schritt 2
Wenn Du das erste mal verbindest dann Klicke auf ![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_start_de.png)
um mit Microbit zu verbinden und klicke immer auf `|Weiter|` klicke schließlich im folgenden Dialog das USB-Gerät auswählen:
![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_de.png)



Klicken Sie schließlich `|Herunterladen|`, um Ihren Code zu übertragen!