# ionic-ipad-issue-margin

This is an issue found on iPad using ionic 5 starter project, it occurs when we present the ionic pages as a modal from an iOS native View, after the keyboard appears the page/margin moves to the right.

## Set up your environment
On the root of the project, run the following on ```cmd```:
```
npm install

ionic build

cap sync
```

After you set-up the environment, open ```../ios/App/App.xcworkspace``` and run the project on iPad, after that click search or a textfield on the app to show the keyboard and the issue would apear.


**Screenshots:**

<img src="https://github.com/blueEagle101/ionic-ipad-issue-margin/blob/main/images/image_1.png?raw=true" width="350">

<img src="https://github.com/blueEagle101/ionic-ipad-issue-margin/blob/main/images/image_2.png?raw=true" width="350">

<img src="https://github.com/blueEagle101/ionic-ipad-issue-margin/blob/main/images/image_3.png?raw=true" width="350">
