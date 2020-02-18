# Holy F****** SHEET, WEB JUST GOT GOOD

## 7./8. - CSS3
Basically just some fooling around with ```box-shadow```, ```text-shadow``` and other 90's animations that now are part of CSS3. Cool stuff but nothing too important, should be definitely checked out and fooled around tho, as there most definitely are effects that look less scuffed.

## 10. FLEXBOXES BABY

Here we finally fkin go.<br>
Flexboxes are boxes (divs) that work pretty dope, only a depth of 1 layer but flex items can be declared as flex boxes.<br>
I worked around not noticing how to define column breakpoints by just adding boxes. Oh my, do I love myself some boxes.

<br>

### display:flex
is how you activate the magic, main(hor) and cross(vert) -axis are orientation markers,
* **justify-content**
  * manipulates main axis
* **align-items**
  * manipulates cross axis
* **flex-direction**
  * ROTATES main axis (holy cow) 
    * :row / row-reverse
    * column / column reverse (go look up pictures m8)

### flex-items

flex items are the elemnts of the flex box, some interestin base values:
* flex-grow: 0 (describes portions used, e.g. 3:1, defined for items seperately)
* flex-shrink: 1 (boolean)
* flex-basis: auto (size)
* order: 0 (order)

There is also a short way to write those down:

 .flex-item {
    flex: 0 1 auto;<br>
    }

### responsive design
```
 @media screen and (min-width:800px) {
}
```
^ describes a styling that only applies to viewports of width 800px and above, it is used to easily make functional code for different devices.
