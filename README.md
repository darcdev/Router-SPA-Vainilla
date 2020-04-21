**Load the route**
	Identify where we are on the site. (Initial load of the route).
		
    loadInitialRoute ()

**Compare the URL with a path**
The URL to which it moves us, must be compared with the routes we have.

    matchUrlToRoute ()

**Update the URL in the navigation bar**
For this we will use the HTML pushState method. 

`windows.history.pushState({},title,url)`

    loadRoute ()
    
**Update the DOM with new content**
For this we are going to use innerHTML.

    loadRoute ()


