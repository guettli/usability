# Usability

This page is my personal barf bag where I write down my dissatisfaction concerning missing usability.

## Desktop Usability

my personal point of view.

- enlarging the mouse coursor should very easy
- the default action should be visible (for example the button which gets "pressed" if I hit ENTER)
- ctrl-plus ctrl-minus should increase/decrease the text size in every application.

Screenshots and anecdotes where software made me think. Thinking hurts - I want to avoid it.


## Ubuntu/Gnome


Nautilus images can not be displayed big. Too small for me:

https://askubuntu.com/questions/1097934/nautilus-show-images-with-more-than-200-size



Gimp: Open jpg/png edit it. Save it. Annoying: Gimp wants to force you into is own image format. The gimp developers know it better than I do. They know what's good for me: a lossless image format. No, this is useless. Most average users want to open a jpg/png edit it, and save a jpg/png again. Experts want a lossless data format. The way of the average user should be the default. Experts can handle this their way.



double-click on a word should mark the thing in all applications. If I double-click on the "o" in path /blu/foo/bar Firefox does mark "foo". In a gnome-terminal the whole path gets selected. This is annoying. Here is how to fix Firefox double-click behaviour: http://kb.mozillazine.org/Layout.word_select.stop_at_punctuation I think Firefox's default should get fixed. Selecting a file path is very common. Chrome has the same strange default like Firefox.




## Gnome panel

### Gnome panel: date stops at end of month.

Today is tuesday July 30. I want to know the date of the next tuesday.
I click on the time symbol at the top of the scree an see this:

![Gnome date stops at end of month.](gnome-date-stops-at-end-of-month.png)

... grrr I don't see that the next tuesday is July 6th.

### Gnome panel: Show date next to time

How do I show date next to time in the panel with gnome-shell? https://askubuntu.com/questions/83597/how-do-i-show-date-next-to-time-in-the-panel-with-gnome-shell The current solutions are way too complicated. I want a solution which gets found by a grandma without using google. It should be simple in the spirit of "don't make me think".

## Server

### /usr/bin/systemctl vs /bin/systemctl

Ubuntu uses /bin/systemctl. SuSE /usr/bin/systemctl. No problem? It is annoying if you want to write sudo-rules which work on both distributions.

### Package name differ

Package names differ across linux distributions. Containers improve this, since this reduces the need to make things portable.
