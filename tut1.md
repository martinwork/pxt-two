# Flashing Heart


## Step 1 @fullscreen

Place a ``||basic:pause||`` and a ``||buttonClicks.onButtonSingleClicked||`` block.

```blocks
buttonClicks.onButtonSingleClicked(buttonClicks.AorB.A, function () {
	
})
basic.forever(function () {
    basic.pause(100)
})
```

## Step 3

Look at the virtual @boardname@, you should see nothing.

## Step 4

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and see nothing there too.
