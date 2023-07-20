# Sensor Display Program


## **Step 1** - Drag  **showLeds**  into the Start blocks.
Click on ``||basic.basic||`` folder to select the ``||basic.showLeds||``. Then, drag the ``||basic.showLeds||`` into ``||basic.Start||`` block.
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)```

## **Step 2** - Drag a second **showLeds**  into the first **showLeds**
Click on the  ``||basic.basic||`` folder  to select the ``||basic.showLeds||``. Then, drag a ``||basic.showLeds||`` place it into ``||basic.showLeds||``
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

## **Step 3** - Drag a third **showLeds** into the second **showLeds**
 Drag  ``||basic.showLeds||`` place it into ``||basic.showLeds||``
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
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)```

## **Step 4** - Drag a fourth  **showLeds** place it into the third **showLeds**
Drag a ``||basic.showLeds||`` into ``||basic.showLeds||``
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
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)```

## **Step 5** - Drag a fifth **showLeds** place it into the fourth **showLeds**.
Drag a ``||basic.showLeds||`` into ``||basic.showLeds||``
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
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)```

## **Step 6** - Drag a ** basic forever loop** from the basic folder.
Click on the ``||basic.basic||`` folder and drag a ``||basic.forever(function ()||`` 
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
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.forever(function ()```

## **Step 7** - Drag a basic **show Number** from the **basic folder** and place it into the **basic forever loop**.
Drag a ``||basic.showNumber()||`` and place it into ``||basic.forever(function())||`` loop
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
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.forever(function () {
    basic.showNumber()
})```

## **Step 7** - Drag  **temperature** from the **Input** folder and place it into the **basic.forever loop**.
Click on the ``||input.input||`` folder and drag a ``||input.temperature()||``  and place it into ``||basic.showNumber ()||``
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
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.forever(function () {
    basic.showNumber(input.temperature())
})```

## **Step 8** - Run the Program
You will add the temperature to display, by clicking on the thermometer. 
You can lower or raise the temperature.
