## HTML
see the ID and Class named 'match___'
these can be named anything, but must match eachother for JS to work. The JS takes the ID and adds a '.' at the beginning to find the class of that name and displays that content
<img src="img/brelaCode1.png">
Could be named the same as title, without spaces.

In this next example they are both named quest 1 ✅
<img src="img/brelaCode2.png">

.listItem is the class name given to all items in the left side items (named Title of Quest 1 - 5 currently )

.displayContent is what shows up in the large section on the screen when you click the listItem

if you copy then paste the commented out template, you have to comment out that line (see blue arrow in 1st pic), and (see title commented out 2nd pic)
this commented out title helps keep each section separated nicely once there is lots of content in each section

## CSS

anything with kyu in the name will probably be renamed

to get rid of line that separates listItems for last list item, :last-child wasn't working for some reason, so .listItem.last is used to remove that line. 
make sure the last item to the bottom of kyu section has .last unless someone can figure out the :last-child problem there