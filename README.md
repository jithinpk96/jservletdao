# This program is an example for servlet.




This program will have switch cases... so every time when i call get,put,delete anything.. then, the request will lead to this method and then goes to respective method you have called. This does not follow DESIGN PRINCIPLE. 

One of the design principle is "Dont repeat yourself".Because once you do this, then if the initial method fails, whole program fails.
Normally, if the program has separate methods then if delete doesn't work, put or get works. Or if any of the method don't work then various other method works.

Inorder to avoid this... just see only how to program in servlet not the pattern of programming.
