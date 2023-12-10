# X-Screensaver Presentation Mode

Sometimes you want to present something on a big screen but your X-Screensaver is not disabled automatically (e.g. because it is a document and not a presentation).

These scripts "install" a possibility to inhibit X-Screensaver manually via a Menu button.

It is not a real install, it just copies 3 scripts:

1) presentationModeOn.service - setting up a user service which, if active, runs indefinitely every 50 seconds and deactivating X-Screensaver
2) _home_user_NonInstalls_xscreensaver_presentationModeOn.desktop - turning the service on
3) _home_user_NonInstalls_xscreensaver_presentationModeOff.desktop - turning the service off

And thats it.

Just run the install-___.sh and you should get your buttons in the Menu.

Let me know how it goes.

Have fun.
Dj