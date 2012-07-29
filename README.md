# JPKeyboardListener

A simple static class for keeping track for that pesky keyboard!


### Usage

Using JPKeyboardListener is easy! Simply add `#import "JPKeyboardListener.h"` with all of the other `#import`s inside your `AppDelegate`. 

Then inside your 

`- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions` 

add the following line above `return YES`:

`[JPKeyboardListener sharedListener];`


### Support

Having trouble with JPKeyboardListener? Feel free to email me: `jack (dot) perry (at) me (dot) com`
