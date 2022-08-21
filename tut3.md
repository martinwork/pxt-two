# tut3

```
https://makecode.microbit.org/#tutorial:https://github.com/martinwork/pxt-two/tut3
```

```package
buttonClicks=github:bsiever/microbit-pxt-clicks
```

## Introduction @unplugged

Learn how to refer to extensions.

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

## Step 2

Look at the virtual @boardname@, and press A.
If you have a @boardname@ connected, click ``|Download|`` to transfer your code, and press A.
