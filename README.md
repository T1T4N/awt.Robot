# awt.Robot

A port of Java's Robot class.
Used to handle keyboard and mouse events and create screen captures.

### Implemented methods:
- CreateScreenCapture
- KeyPress (using user32.dll:keybd_event)
- KeyRelease (using user32.dll:keybd_event)
- MouseMove (using System.Windows.Forms.Cursor)
- MousePress (using user32.dll:mouse_event)
- MouseRelease (using user32.dll:mouse_event)
- MouseWheel (using user32.dll:mouse_event)
