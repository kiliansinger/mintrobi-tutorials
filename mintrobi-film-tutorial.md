# mintrobi-film-tutorial
## Step 1
First insert a ``show LEDs`` block:
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
Then insert several in a row and make a film of a laser gun, for example:
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
## Step 3
When you connect for the first time, do the following:
* Click on the 3 white dots on the blue field.
* Then click on Connect Device:
![Start device connection](https://kiliansinger.github.io/mintrobi-tutorials/connect_start_de.png)
* Then click on `|Next|` again and again.
* Then a dialogue opens, select here as follows:
![Start Connecting Device](https://kiliansinger.github.io/mintrobi-tutorials/connect_de.png)

The `|Download|` button should then look like this:
![Download on Microbit](https://kiliansinger.github.io/mintrobi-tutorials/download_microbit.png) 

Then click on `|Download|` to transfer your code!

Press the reset Button on the back side of the microbit if youy want to restart the code:
![Reset Button](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/19067466923/original/iPH690ko6mt0STYSgz8v_sYFUoz4BnlJsQ.png?1604662044)