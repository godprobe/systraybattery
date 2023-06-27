# SysTrayBattery

Adapted and cleaned up from ChatGPT prompts!


Creates a System Tray icon with a percent battery remaining tooltip.

Uses the first encountered system battery: battery.Get(0)


Currently supporting only Windows.

The icon byte data is from an .ico file, which should be cross-platform.

The systray.SetTooltip() function only supports Windows and Mac.

Tested only on Win 11 Home, 64-bit, on a $100 Black Friday laptop!


For the future:
- (version 1.0) Replace the icon with a text representation of the battery percentage remaining.
- Tests...
- Overlay the text on top of a battery image, depending on how that looks.
- Create the battery image dynamically, from full to empty.
- (?) Multi-platform
- (?) Settings and preferences
