# smartsemicolon
## Automatically exported from https://code.google.com/p/smartsemicolon/ (https://archive.is/ExfMJ)

The Smart Semicolon Eclipse plug-in lets you quickly insert a semicolon (and optionally a new line and indent) at the end of Java statement source line.

**Note:** It turns out, Eclipse already has a very similar feature which can be found at **Window > Preferences > Java > Editor > Typing > Automatically insert at correct position > Semicolon**. Take your pick.

**Update Site:** https://raw.githubusercontent.com/raphaeldore/smartsemicolon/master/SmartSemicolonUpdateSite/site.xml

Here is an example of how it works:

If you have a line like this in your Java Editor:

![step1](https://cloud.githubusercontent.com/assets/946742/9699807/051e2ae2-53bd-11e5-8007-15fe051ef13c.png)

where ``|`` is where the caret is and if you type <tt>Control+;</tt> you will get:

![step2 1](https://cloud.githubusercontent.com/assets/946742/9699810/05222b92-53bd-11e5-95a9-4939e40db251.png)

**Note** The caret is left where it was.

Similarly if you type <tt>Shift+Control+;</tt> you will get:

![step2 2](https://cloud.githubusercontent.com/assets/946742/9699809/052134ee-53bd-11e5-9cf3-ddab76857379.png)

**Note** A properly indented new line is added and the caret is moved to the new line.

Also added support for inserting comma, which is useful while writing array initializer.

**Commands**

*   Add semicolon ( <tt>Control+;</tt> )
*   Add semicolon, newline and indent ( <tt>Shift+Control+;</tt> )
*   Add comma ( <tt>Control+,</tt> )
*   Add comma, newline and indent ( <tt>Shift+Control+,</tt> )

**Note** Use <tt>Command</tt> key in place of <tt>Control</tt> on Mac OS.

The key bindings can be changed using **Preferences > General > Keys** preferences page. The commands can be found under **Text Editing** category.

![keysprefs](https://cloud.githubusercontent.com/assets/946742/9699806/051cc09e-53bd-11e5-935f-26c9a2c60b44.png)
