# iOS 11.3 Cordova Paste Bug.


To reproduce:

```
git clone git@github.com:ccorcos/cordova-paste-bug.git
npm install
npm run build
npm run xcode
```

Run the iOS app on your phone or in the simulator.

Follow the instructions in the app:

> Select some text in the input below and copy it to the clipboard. Then paste. You should see "It worked!" in the input but on iOS 11.3, you won't.
