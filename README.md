
# Use Sublime Text to Copy Lines To Bottom of File


I have a long file of quotes. Using Sublime Text and a Mac, I want to copy specific ones to the bottom, then return to the same spot in the text file.

This is a macro to do just that.

To activate the F2 key, remember to hold the 'fn' key in the very bottom left of the keyboard while hitting the F2 key.

When you are first recording the macro, put the cursor at the start of the line you want to copy to the bottom.

CTRL+Q; start recording macro

CMD+F2; toggle bookmark

SHIFT+DownArrow; highlight line

CMD+C; copy line

CMD+DownArrow; go to bottom of file

CMD+V; paste line

SHIFT+F2; go to previous bookmark

CMD+SHIFT+F2; clear bookmark

CTRL+Q; stop recording macro

Now put the cursor in front of the line you want to copy and move down and:
CTRL+SHIFT+Q; activate macro

Hope that's useful.

2013-07
Jesse Cummins
https://github.com/jessc
