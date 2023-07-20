# Sensor Display Program
## **Step 1** - Drag a LED lights into the Start blocks
Drag a ``||LED lights||`` into ``||basic.showLeds||``
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)```

## **Step 2** - Drag a second LED lights into the LED lights
Drag a ``||LED lights||`` into ``||LED lights||``
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)```