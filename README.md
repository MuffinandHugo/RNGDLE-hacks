
Step 1: Copy the Eruda Code

Copy this exact single line of JavaScript:
javascript
javascript:(function () { var script = document.createElement('script'); script.src="https://jsdelivr.net"; document.body.appendChild(script); script.onload = function () { eruda.init() } })();
Use code with caution.

Step 2: Create a Dummy Bookmark in Safari

1. Open Safari and go to any normal website (like apple.com or google.com).
2. Tap the Share icon (the square with an arrow pointing up) at the top right of the screen.
3. Scroll down and tap Add Bookmark.
4. Change the name to Eruda Console and tap Save.

Step 3: Paste the Code Into the Bookmark

1. Tap the Sidebar icon (the square with a sidebar on the left) at the top-left corner of Safari.
2. Tap Bookmarks (the open book icon).
3. Tap Edit at the bottom right of the bookmarks list.
4. Tap on your Eruda Console bookmark.
5. Tap the URL box, tap the small X (or Select All -> Delete) to clear out the old website link, and tap Paste to put in the javascript:(function ()... code.
6. Tap Done at the top right, then tap Done again at the bottom right.

Step 4: Launch the Console on Any Website

1. Go to the webpage you want to inspect.
2. Tap the Sidebar icon at the top left -> Bookmarks -> tap Eruda Console. (Alternatively, tap the address bar, type Eruda Console, and tap the bookmark option that pops up.)
3. Look at the bottom-right corner of the screen—a floating gear icon will appear. Tap it to open the developer console!
(Note: On some school iPads or strict websites, school content filters or website security settings may block the external cdn.jsdelivr.net script from loading.)
