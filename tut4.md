# tut4

```package
whatshouldthisbe=github:bsiever/microbit-pxt-clicks
```

## Introduction @unplugged

Learn how to make a tutorial 


## Step 1 @fullscreen

Place a ``||basic:pause||`` block, and a ``||buttonClicks:onButtonSingleClicked||`` block.

```blocks
buttonClicks.onButtonSingleClicked(buttonClicks.AorB.A, function () {
	basic.showString('A')
})
basic.forever(function () {
    basic.pause(1000)
    basic.clearScreen()
})
```

## Step 3

Look at the virtual @boardname@, and press A.

## Step 4

If you have a @boardname@ connected, click ``|Download|`` to transfer your code, and press A.
