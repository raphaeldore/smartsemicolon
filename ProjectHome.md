The Smart Semicolon Eclipse plug-in lets you quickly insert a semicolon (and optionally a new line and indent) at the end of Java statement source line.

**Note:** It turns out, Eclipse already has a very similar feature which can be found at **Window > Preferences > Java > Editor > Typing > Automatically insert at correct position > Semicolon**. Take your pick.

**Update Site:** ` http://smartsemicolon.googlecode.com/svn/trunk/SmartSemicolonUpdateSite/site.xml `

Here is an example of how it works:

If you have a line like this in your Java Editor:

![http://smartsemicolon.googlecode.com/files/step1.png](http://smartsemicolon.googlecode.com/files/step1.png)

where | is where the caret is and if you type `Control+;` you will get:

![http://smartsemicolon.googlecode.com/files/step2.1.png](http://smartsemicolon.googlecode.com/files/step2.1.png)

**Note** The caret is left where it was.

Similarly if you type `Shift+Control+;` you will get:

![http://smartsemicolon.googlecode.com/files/step2.2.png](http://smartsemicolon.googlecode.com/files/step2.2.png)

**Note** A properly indented new line is added and the caret is moved to the new line.

Also added support for inserting comma, which is useful while writing array initializer.

**Commands**

  * Add semicolon ( `Control+;` )
  * Add semicolon, newline and indent ( `Shift+Control+;` )
  * Add comma ( `Control+,` )
  * Add comma, newline and indent ( `Shift+Control+,` )

**Note** Use `Command` key in place of `Control` on Mac OS.

The key bindings can be changed using **Preferences > General > Keys** preferences page. The commands can be found under **Text Editing** category.

![http://smartsemicolon.googlecode.com/files/keysprefs.png](http://smartsemicolon.googlecode.com/files/keysprefs.png)
