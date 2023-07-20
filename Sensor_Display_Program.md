# Sensor Display Program




## Step 1
Under the **toolbox** Click on ``||basic.basic||`` folder to select the ``||basic.showLeds||`` block.
Then, drag the ``||basic.showLeds||`` into ``||basic.Start||`` block.
Think about what you want to animate. How you want to display your animation in 5 steps.
For example, the letter **E**
```blocks
basic.showLeds(`
# # # # #
# # # # #
# # # # #
# # # # #
# # # # #
`)
```


## Step 2
Click on the ``||basic.basic||`` folder to select a second ``||basic.showLeds||`` block.
Then, drag a ``||basic.showLeds||`` place it into the first ``||basic.showLeds||``
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
```


## Step 3
Drag a third ``||basic.showLeds||`` block and place it into second ``||basic.showLeds||``
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
```


## Step 4
Drag a fourth``||basic.showLeds||`` block and place it into third ``||basic.showLeds||``
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
```


## Step 5
Drag a fifth ``||basic.showLeds||`` block and place it into the fourth``||basic.showLeds||``
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
```




## Step 6
Drag a ``||basic.showNumber()||`` and place it into ``||basic.forever()||`` loop 

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
```
```blocks
basic.forever(function () {
    basic.showNumber()
})
```

## Step 7
Under the **toolbox** Click on the ``||input.input||`` folder and drag a ``||input.temperature()||`` and place it into ``||basic.showNumber ()||``


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
```
``` blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```



## Step 7
To run the program you will click on the thermometer to display the temperature.
You can lower or raise the temperature.
