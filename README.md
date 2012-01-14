Development is starting again after a long break
--

Corlanthia is an in-development text adventure game written in Java.

Corlanthia has some basic features implemented; so far users can move cardinally, inspect items, pickup items, see their inventory, drop one or many items, look in the room to see what objects are there. There is also a "debug" command that so far adds items to a room and displays all of the items in the room.

With the way that books are implemented, there can only be one per room.

Update v0.1.9
--

+ Added command 'lookat' to replace look, works the same as inspect
+ Added new debug command 'look', is alias to 'showitems'
+ Added Debug.java
+ Added letter item
+ Implemented function to read a book or a letter
* Moved debug method from Actions.java to Debug.java
* Re-coded inspect method and is now much more versatile
* Merged all <Item>Desc arrays into a multi dimensional array
- Removed 'look' command (still remains in debug though)
- Removed CheckRoom and CloseRoom methods


Next Update
--

* Cleaner code
* Bug fixes
* Much better NPC support
* Overhaul of how NPCs are handled


License Info
--

Corlanthia is protected by the Creative Commons Attribution 3.0 Unported License. More information about the license can be found here: http://creativecommons.org/licenses/by/3.0/