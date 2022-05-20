# keylogger
keylogger and a screenshoot taker
install PyHook to be able to run thus keylogger


This uses an excellent Python library named PyHook which enables us to easily trap all keyboard events. It takes
advantage of the native Windows function SetWindowsHookEx, which allows you to install a user-
defined function to be called for certain Windows events. By registering a hook for keyboard events,
we are able to trap all of the keypresses that a target issues. On top of this, we want to know exactly
what process they are executing these keystrokes against, so that we can determine when usernames,
passwords, or other tidbits of useful information are entered.


This has the capability to take screenshots
against the remote target. This can help capture images, video frames, or other sensitive data that you
might not see with a packet capture

This will use the Windows Graphics Device Interface (GDI) to determine necessary
properties such as the total screen size, and to grab the image. Some screenshot software will only
grab a picture of the currently active window or application, 
