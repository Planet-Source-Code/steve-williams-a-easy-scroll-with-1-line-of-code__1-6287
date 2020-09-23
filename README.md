<div align="center">

## A easy Scroll with 1 line of code


</div>

### Description

Scroll a label with just one line of code...great for showing credits!!!!
 
### More Info
 
You will need a timer and set the interval to 1

and of course a label with whatever you want to say. In this example position the label toward the bottom of the form

Put this in your timer event

Bottom to Top Scroll

1) Use the move method; label1.Move

2) Keep the labels Left property the same;

label1.move label1.left

3) Move it by subtracting from the top

label1.Move label1.Left, label1.Top - 10

Thats it...It don't get any easier than this!

For a faster scroll just subtract more from the top;

ie: label1.Move label1.Left, label1.Top - 50

Side Scroll "Marquee"

label1.Move label1.Left - 10

The Top is optional as well as the Width and Height

It will give the same amount of flicker as the others do but why write all that code to do the same purpose?


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Steve Williams](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/steve-williams.md)
**Level**          |Intermediate
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/steve-williams-a-easy-scroll-with-1-line-of-code__1-6287/archive/master.zip)





### Source Code

```
Private Sub Timer1_Timer()
  Label1.Move Label1.Left, Label1.Top - 10
End Sub
```

