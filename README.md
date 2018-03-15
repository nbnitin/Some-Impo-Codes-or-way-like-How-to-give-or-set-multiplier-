# How-to-give-or-set-multiplier-

Put a view inside a parent view
give it a constraint except what you want to set like eight width or height.
and drag child to parent by holding ctrl button and choose equal width / height as you want.

and in child constraint select and edit height/width constraint. defualt multiplier will be 1.

now divide child view width/height what you want to give it by width/height of parent. the result will be your multiplier.

E.x.

I put view inside a cell
my cell width is 414 and i want view width is half of cell always.
414/2 = 207 is my view width.

and gave leading top and bottom contraint but not width.
now select this child view and drag it to parent cell and select equal width.
now in size inspector window select this view's width and edit it.
divide 207 / 414 = 0.5 this is your mutliplier.
