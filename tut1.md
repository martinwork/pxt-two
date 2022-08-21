# Flashing Heart

```
https://makecode.microbit.org/#tutorial:https://github.com/martinwork/pxt-two/tut1
```

## Introduction @unplugged

Learn how to make a tutorial 


## Step 1 @fullscreen

Place a ``||basic:pause||`` block in the ``||basic:forever||`` block.

```blocks
basic.forever(function () {
    basic.pause(100)
})
```

## Step 2

Place a ``||buttonClicks.onButtonSingleClicked||`` block.

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
