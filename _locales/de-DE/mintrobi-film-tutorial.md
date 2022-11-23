# mintrobi-film-tutorial
## Step 1
Füge den Zeige LEDs Block zum ``beim Start`` Block hinzu.
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```
## Step 2
Legen füge mehrere hintereinander ein um einen Film von z.B. einer Laserkanone zu machen.
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
})
```
## Step 3 @showhint
Wenn Du das erste mal verbindest dann gehe wie folgt vor:
* Klicke auf die 3 weißen Punkte auf dem blauen Feld.
* Dann auf Gerät verbinden:
![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_start_de.png)
* Dann klicke immer wieder auf `|Weiter|`
* Dann öffnet sich ein Dialog hier wie folgt auswählen:
![Gerät verbinden starten](https://kiliansinger.github.io/mintrobi-tutorials/connect_de.png)

Der `|Herunterladen|` Knopf sollte dann so aussehen:
![Herunterladen auf Microbit](https://kiliansinger.github.io/mintrobi-tutorials/download_microbit_de.png) 

Dann auf `|Herunterladen|` klicken, um Ihren Code zu übertragen!

Drücke die Reset-Taste auf der Rückseite des microbit, falls Du den Code neu starten willst:
![Reset Button](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/19067466923/original/iPH690ko6mt0STYSgz8v_sYFUoz4BnlJsQ.png?1604662044)