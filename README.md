# platform_view_bug

Problem: When using a hardware mouse on Android, clicks can go through PlatformViews when they are inside an Offstage widget.

To reproduce:
1. Run the app on an Android device.
2. Connect a hardware mouse or emulate it with `scrcpy --hid-mouse`
3. Tap the button in the home tab, it will be tapping some video from the Youtube platform view in the second tab.