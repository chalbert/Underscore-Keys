#Underscore-Keys

Few utilities to work with key events.

### isKeyEvent(event)
Return true if the event is keypress, keydown or keyup.
        
    _.isKeyEvent('keypress');  // True
    _.isKeyEvent('click');  // False

### isKey(key)
Return true if the string is correspond to the name of a key.
    
    _.isKey('enter'); // True
    _.isKey('foo'); // False
    
### getKeyCode(key)
Return the keycode from the name of the key.

    _.getKeyCode('enter'); // 13
    
### getKey(code)
Return the name of the key from the keycode.

    _.getKey(27); // 'escape'