# Flashing Heart

## Introduction

Learn how to use the LEDs and make a flashing heart! 
(Want to learn how lights work? [Watch this video](https://youtu.be/qqBmvHD5bCw)).


![Heart shape in the LEDs](/static/mb/projects/flashing-heart/sim.gif)

## Step 1 

Place the ``||basic:show leds||`` block in the ``||basic:forever||`` block and draw a heart.

![An animation that shows how to drag a block and paint a heart](/static/mb/projects/flashing-heart/showleds.gif)

## Step 2

Place another ``||basic:show leds||`` block. You can leave it blank and draw what you want.

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .`);
})
```

## Step 3

Look at the virtual @boardname@, you should see the heart and your drawing blink on the screen.

## Step 4

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and watch the hearts flash!

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
