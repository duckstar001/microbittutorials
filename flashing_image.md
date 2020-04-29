# Make a flashing image

## Step 1

First find the forever block.

```blocks
basic.forever(function () {
 
})
```

## Step 2

Add the show ``image block`` and draw an image.

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```

## Step 3

Add a pause and a clear screen block.

```blocks
basic.forever(function () {
    basic.showLeds(`
        # # . # #
        # # . # #
        . . . . .
        # . . . #
        . # # # .
        `)
    basic.pause(100)
    basic.clearScreen()
})
```
