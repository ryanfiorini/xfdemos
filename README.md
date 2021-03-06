Basic demo xamarin forms app base - actual demo apps/functions will be built into or forked from this.

## Custom Switch - Change Colour Based on On/Off State

See [CustomControlPage](https://github.com/wislon/xfdemos/blob/master/src/xamformsdemo/xamformsdemo/CustomControlsPage.xaml) example.  I wrote a [blog post about it](http://blog.wislon.io/posts/2017/05/15/xamforms-change-switch-colour).

### Android implementation
Before implementation on Android. Note that you can't see the track of the `Switch` when it's off ('false').

![Android - Before implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/customcontrols/switch-before-droid.gif)

After adding some garish colours:

![Android - After implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/customcontrols/switch-after-droid.gif)

### iOS implementation
Just proving the concept on iOS. Before...

![iOS - Before implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/customcontrols/switch-before-ios.gif)

...and after.

![iOS - After implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/customcontrols/switch-after-ios.gif)

--- 

## ListView Item Selection - Change its background colour:

See [ListViewDemoPage](https://github.com/wislon/xfdemos/blob/master/src/xamformsdemo/xamformsdemo/ListViewDemoPage.xaml) example.  I also wrote a [short blog post about it](http://blog.wislon.io/posts/2017/04/11/xamforms-listview-selected-colour).

_(Apologies for the janky iOS gifs, they were done from the simulator running over a long-distance wifi connection)_

### iOS implementation
Before implementing on iOS. Note that you can't tell when an item is selected.

![iOS - Before implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/listviewcolor/ios-before.gif)

After implementing on iOS (change selected colour to teal)

![iOS - After implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/listviewcolor/ios-after.gif)

### Android implementation
Before implementing on Android (ugh orange, from the default theme)

![Android - Before implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/listviewcolor/droid-before.gif)

After implementing on Android (better, teal)

![Android - After implementation](https://github.com/wislon/xfdemos/blob/master/screenshots/listviewcolor/droid-after.gif)

