# mintrobi-noise-tutorial
## Schritt 1
Nehme z.B. den Film als Vorlage und füge den
``||music:spiele Ton kichern||`` Block unten an.
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
## Schritt 2 @showhint
Wenn Du das erste mal verbindest dann gehe wie folgt vor:
* Klicke auf die 3 weißen Punkte auf dem blauen Feld.
* Dann auf Gerät verbinden:
![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_start_de.png)
* Dann klicke immer wieder auf `Weiter`
* Dann öffnet sich ein Dialog hier wie folgt auswählen:
![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_de.png)

Der `Herunterladen` Knopf sollte dann so aussehen:
![Herunterladen auf Microbit](https://kiliansinger.github.io/mintrobi-tutorials/download_microbit_de.png) 

Dann auf `Herunterladen` klicken, um Ihren Code zu übertragen!

Drücke die Reset-Taste auf der Rückseite des microbit, falls Du den Code neu starten willst:
![Reset Button](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/19067466923/original/iPH690ko6mt0STYSgz8v_sYFUoz4BnlJsQ.png?1604662044)