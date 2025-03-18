The HapticsInShortcuts app can be found here: https://apps.apple.com/fi/app/hapticsinshortcuts/id6743251490
If this app is no longer in the appstore, it means, that my developer membership expired, and i've decided not paying for that any longer.

The app main purpose is providing the haptics efects to the ios and watchOS shortcuts actions.
This app makes possible some haptics effects for both iPhone and an apple watch.

Another important thing, is this app allows getting one of the 18 possible orientation positions of the iPhone or an apple watch using the shortcuts (apple's built in shortcuts app).
Depending on the orientation position of the device, one of 18 different actions can be performed. It means, one actions button (on the watch or an iPhone) will make one of 18 possible actions depending on the device orientation position.
If the device does not have the action button, the script can be run using the assestive touch->hand gestures->tap/double tap/clench or the double clench. 
If there is no action button on the iphone, script can run when iphone opens the zoom app(magnifier prebuilt app). The magnifier/zoom app launch can be done in the accessibility->accessibility shortcut, choose the "Magnifier" there. Then, in the shortcuts app go to an automations tab, and add a new automation, which works when an app is opened. For an app, which opening should trigger an automation, choose the "Magnifier" app.
Then, by triple pressing the side-button, the Magnifier app will be opened, and the shortcuts automation will run. In the shortcuts automation the "Get Device Angles" action will return the device's orientation angles + the one of 18 orientation positions the devie currently on.
Yes, there are prebuilt "get orientation" action, but this one DOES NOT work on the apple watch, and it returns only one of 6 orientation positions on the iPhone (not 18).
