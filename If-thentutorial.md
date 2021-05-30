# If-thentutorial
## Step 1

Drag the ``||Basic:on start||`` block to the trash on the left main menu.
 
## Step 2
In the menu on the left. Click on the  ``||Logic:logic||``, drag the ``||Logic:If then||`` block inside the ``||Basic:Forever||`` block.
```blocks
basic.forever(function () {
    if (true) {
       
    }
})
```
 
## Step 3
Click the ``||Input:Input||`` block, drag the ``||Input:pin P0 is pressed||`` block and replace the ``||Logic:true||`` inside the ``||Logic:logic||`` block.
```blocks
basic.forever(function(){
if (input.pinIsPressed(TouchPin.P0)) {
       
    }
})
```
 
## Step 4
Click the ``||Basic:on start||``, drag the ``||Basic:show string "Hello"||`` block inside the  ``||Basic:forever||``block.
```blocks
basic.forever(function () {
    if (input.pinIsPressed(TouchPin.P0)) {
        basic.showString("Hello!")
    }
})
})
```
 

## Step 5
Connect the Micro:bit to the USB port on your computer. Then click on ``||LED:Download||`` (Make sure that you download the file to the Micro:bit drive")
```blocks
basic.forever(function () {
    if (input.pinIsPressed(TouchPin.P0)) {
        basic.showString("Hello!")
    }
})
```
## Step 6
Congratulations, you did it!