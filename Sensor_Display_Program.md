# Sensor Display Program

## Step 1- Drag the LED Lights into the clearScreen block
Drag a ``||basic.showLeds||`` into the ``||basic.Start||``
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)```


## Step 2- Drag the LED Lights into LED Lights
Drag a second ``||basic.showLeds||`` into the ``||basic.showLeds||``
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

## Step 3- Drag a third  LED Lights into LED Lights
Drag a third ``||basic.showLeds||`` into the ``||basic.showLeds||``
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

## Step 4- Drag a fourth  LED Lights into LED Lights
Drag a fourth ``||basic.showLeds||`` into the ``||basic.showLeds||``
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

## Step 5- Drag a fourth  LED Lights into LED Lights
Drag a fifth ``||basic.showLeds||`` into the ``||basic.showLeds||``
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

## Step 6- Drag a basic forever function
Drag a ``||basic.forever||`` function and place it on the top.
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

## Step 7- Drag a basic forever function
Drag a ``||basic.showNumber(input.temperature()||`` function and place it on ``||basic.forever||`` .
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



  
