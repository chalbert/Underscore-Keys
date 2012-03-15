#Underscore-Keys

Few utilities to work with key events.

### isKeyEvent(event)
Return true if the event is keypress, keydown or keyup.
        
    _.isKeyEvent('keypress');  // True
    _.isKeyEvent('click');  // False

### isKey(key)
Return true if the string correspond to a key, either special or normal.
    
    _.isKey('enter'); // True
    _.isKey('foo'); // False
    _.isKey('t'); // True
        
### getKeyCode(key)
Return the keycode from the name of the key.

    _.getKeyCode('enter'); // 13
    // Works also for normal keys - letters, numbers, etc.
    _.getKeyCode('w'); // 87
    
### getKey(code)
Return the name of the key from the keycode.

    _.getKey(27); // 'escape'
    _.getKey(54); // 6
    
### Supported special keys

    backspace tab enter shift ctrl alt capslock escape pageup pagedown end home left up right down insert delete