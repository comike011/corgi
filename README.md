= corgi

This gem adds the power and finesse of corgis to your demo site where temp content is needed. 

Add 
	require placecorgi 

to your application.js file so that it will be included, then wherever you need a place corgi define an image tag as such: 

	<img src="" height=[height] width=[width] class="corgi"> 

and a corgi will be added matching the desired dimensions. If invalid or empty values are sent for the dimensions it will default to 300 x 300.

== Contributing to corgi
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

== Copyright

Copyright (c) 2012 Mike Calhoun. See LICENSE.txt for
further details.
