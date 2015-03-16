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
	- use negative margin top to pull .profile picture partly 
	- use position: relative to make sure profile remains in front of content header 
	- use pseudo selectors to get divider lines 

* Online Ribbon  
	- Adding a fancy online ribbon to profile image
	- Use transform to animate

* Thumbnails  
	- Use list and float to grid out thumbnails
	- Use :nth-child() pseudo-selector to add left and right margins every so li's
	- Use before and after selectors to inject attr data and triangular tooltip

* Forms  
	- Can reuse .thumb class css
	- When floating a block element, width is determined by content
	- Set width manually to fill up space
	- CSS can do math with calc()

* Posts
	- Use semantic tags to make posts
	
* Icons
	- Sprites reduce HTTP requests overload
	- [class*="icon-"] pseudo-selector
	- use inline-block to set width and height of icons
	- use CSS to push text ouf of the box
	- Repurpose <i> tag for icons
	- Interesting to note that to apply the sprites, one has to slide and position the sprite sheet accordingly

* Modal
	- Created at bottom of the page
	- Use a jquery to enable toggling