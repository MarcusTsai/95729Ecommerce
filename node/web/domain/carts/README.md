The /carts directory contains two files: Cart.js and History.js

Cart.js defines the model of the shopping cart.
<p>Shopping cart schema has two parts:</p>
<p>
	<li> book array contains all the book products, and quantity respectively </li>
	<li> amount represent the total amount in the shopping cart </li>
</p>
<p> Methods in Cart.js includes: </p>
<p>
	<li> Add one book to the shopping cart </li>
	<li> Remove one book from the shopping cart (quantity changes) </li>
	<li> Remove one book item from the shopping cart (remove the entire book item) </li>
	<li> Merge two shopping carts (corner cases) </li>
</p>