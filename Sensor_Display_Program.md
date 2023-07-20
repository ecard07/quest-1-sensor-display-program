# Sensor Display Program


## Step 1 
Under the **toolbox** Click on ``||basic.basic||`` folder to select the ``||basic.showLeds||``. 
Then, drag the ``||basic.showLeds||`` into ``||basic.Start||`` block.
Think about what you want to animate. How you want them to display in 5 steps. 
For example, the letter **E**
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)```

## Step 2
Click on the  ``||basic.basic||`` folder  to select the ``||basic.showLeds||``. 
Then, drag a ``||basic.showLeds||`` place it into ``||basic.showLeds||``
Continue your animation
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

## Step 3 
 Drag  ``||basic.showLeds||`` place it into ``||basic.showLeds||``
 Continue your animation
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

## Step 4 
Drag a ``||basic.showLeds||`` into ``||basic.showLeds||``
Continue your animation

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

## Step 5
Drag a ``||basic.showLeds||`` into ``||basic.showLeds||``
Continue your animation

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

## Step 6
Click on the ``||basic.basic||`` folder and drag a ``||basic.forever(function ()||``
Continue your animation

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

## Step 7
Drag a ``||basic.showNumber()||`` and place it into ``||basic.forever(function())||`` loop
Finish your animation

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
})```

## Step 7
Under the **toolbox** Click on the ``||input.input||`` folder and drag a ``||input.temperature()||``  and place it into ``||basic.showNumber ()||``

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
})```

## Step 8
To run the program you will click on thermometer to display the temperature. 
You can lower or raise the temperature.
