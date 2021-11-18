# jbook-initial
A CLI (command line interface) to boostrap a web app to write/run/document javascript code in the browser.

This won't work without node.js installed on your systems.

To start the app type in your terminal :- "npx xoldyckk-jbook serve"

In your browser open up the following URL :- http://localhost:4005

Click on the respective buttons code/text to choose between a code window and a text window.

The code written executes whenever after every 750 milliseconds you haven't made any changes to the code.
The app detects that nothing is being done for 750 milliseconds and processes the code.

There is a special function embedded into the source code of the code editor called show().
This show function embeds whatever is written inside it into the #root element of the preview window.
So, you can try out writing some HTML code inside the show() function (show(<h1>This is inside show</h1>))
and see the display on the preview window.

Whenever you're done writing code click on the save button on the bottom right on the page.
It will save your code/text inside a file called notebook.js and load it back up when you re-run the app.

Make sure not to do something miscellaneous. The app might break. It's not battle tested at all. It's still got many bugs/errors.
But since this is a demo application I didn't bother to fix everything. It just works.
If sometimes it doesn't work just restart/refresh the app.
