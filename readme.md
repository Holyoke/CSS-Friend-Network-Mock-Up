## Social Network Mock Up ##
This project is an exercises to replicate familiar social network designs.

## Development ##
+ Header
	- Box-sizing set to inherit so all elements behave the same  
	- Clearfix added  
	- Added Google Font  
	- Using "#" to avoid page reloads  
	- Used left and right auto margins to center element
	- Whenever one floats, one will need to clearfix
* Notifications
	- Combine :hover selector and display property to hide dropdown
	- use white-space property to keep notification text on one line
	- use overflow property to fix items poking through bottom 
	- z-index does not work on static, non positioned elements to ensure header dropdown will stay on top

* Layout 
	- to create whitespace use margin and padding
	- use pseudo-content w/ absolute positioning to inherit parent containers
	- be mindful of coordinate system, so control by setting parent element to relative

* Footer  
	- Floats in floats

* Cats 
	- Use text-shadow property to increase contrast on text
	- set line-height to 1 in order to have large fonts not wrap

* Sidebar
	-use negative margin top to pull .profile picture partly 
	-use position: relative to make sure profile remains in front of content header 
	-use pseudo selectors to get divider lines 

* Online Ribbon  
* Thumbnails  
* Forms  
* Posts
* Icons
* Modal