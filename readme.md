# DAB

Open up Konami.html and type "dab". It uses an eventlistener that listens to keystrokes in a certain pattern. If you type dab it it shows you something cool. If you type "crap" shows you something Duke Nukemish funny.

It's written in JQuery, and it adds your keypresses to an array. Then converts the array to a string then compares the string.

I learned from this, you cannot compare an array to an array. It will always be false, because they may have the same contents, but they are in different locations in memory. That's how that was explained to me.