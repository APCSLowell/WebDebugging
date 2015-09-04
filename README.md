# Help! My program runs in Processing but not on the web
To display our AP Java programs on the web, we're using [Processing.js](http://processingjs.org/). Not all Processing functions are compatible with processing.js. You can check [this list](http://processingjs.org/reference/) of supported functions.  

Other problems that could cause your program not to work on the web are:
- Naming a variable with the same name as a function
- Naming a function with a name that is already used in Processing
- Using an image as an argument in `background()`
- `Using System.out.println()`
- Using decimals for x and y coordinates
- Integer division
- Extra semi-colons

You can find the error message for your webpage by opening the *web console* or *javascript console* in your browser.
