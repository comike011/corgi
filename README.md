# corgi #

This gem harnesses placecorgi.com to add the power and finesse of the noble corgi to your demo site where temp content is needed.

## Usage ##

In your application.js file (assuming Rails 3.1+ using the asset pipeline)

  ```javascript
	//= require placecorgi
  ```

In your html, just add a `corgi` class to any image you want to replace with a corgi. Make sure you have the width and height attributes set on the element.

  ```html
	<img src="/assets/my-boring-image.png" width="480" height="320" class="corgi" />
  ```

If invalid or empty values are set for the dimensions it will default to 300 x 300.

# Copyright

Copyright (c) 2012 Mike Calhoun. See LICENSE.txt for
further details.

