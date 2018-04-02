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

> Open up an app like Messages, type some content, copy it to your clipboard and try to paste it into the input below.

You will notice that it doesn't work. When you inspect the clipboardData from the paste event, there is nothing to paste.