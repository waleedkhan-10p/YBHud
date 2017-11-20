# YBHud
A progress hud using [DGActivityIndicatorView](https://github.com/gontovnik/DGActivityIndicatorView)

### Screenshot
![](https://github.com/YahyaBagia/YBHud/blob/master/YBHud/Images/YBHud.gif)

### Installation
Drag and Drop files (YBHud.h & YBHud.m) from YBHud Directory into your XCode Project Directory. Add DGActivityIndicatorView in your project.

### Usage
```sh
YBHud *hud = [[YBHud alloc]initWithHudType:DGActivityIndicatorAnimationTypeCookieTerminator]; //Initialization

//Optional Tint Color (Indicator Color)
//hud.tintColor = [UIColor blackColor];

//Optional User Interaction
//hud.UserInteractionDisabled = YES; (User can interact with background views while HUD is displayed)

//Optional HUD Color
//hud.hudColor = [UIColor yellowColor];

//Optional Dim Amount of HUD
//hud.dimAmount = 0.5;

//Display HUD
[hud showInView:self.view animated:YES];

//Dismiss HUD
[hud dismissAnimated:YES];
```
### Requirements
iOS 9.0+

### License
MIT License
