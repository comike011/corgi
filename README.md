# corgi

This gem adds the power and finesse of corgis to your demo site where temp content is needed. 

Add 
	require placecorgi 

to your application.js file so that it will be included, then wherever you need a place corgi define an image tag as such: 

	<img src="" height=[height] width=[width] class="corgi"> 

and a corgi will be added matching the desired dimensions. If invalid or empty values are sent for the dimensions it will default to 300 x 300.

# Copyright

Copyright (c) 2012 Mike Calhoun. See LICENSE.txt for
further details.

