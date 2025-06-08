# Gaming Performance Booster Magisk Module

This Magisk module is designed to optimize your Android device for gaming with faster GPU rendering and CPU performance.

## Features
- Boosts CPU performance by setting governors to performance mode
- Enhances GPU rendering speed and responsiveness
- Optimizes memory management for games
- Reduces input lag and improves touch response
- Safely manages thermal settings for better performance
- Network optimizations for online gaming
- Toggle between gaming mode and normal mode
- Built-in bootloop protection
- Compatible with Android 10 and above

## Safety Features
This module includes multiple safety measures to prevent bootloops:
- Automatic module disabling after 3 failed boots
- Gradual performance ramping on first boot
- Adaptive performance based on Android version (safer on Android 10, more aggressive on Android 11+)
- Device-specific parameter detection to prevent incompatibilities
- All system modifications are checked for existence before applying
- Safe mode is the default state after installation

## Installation
1. Download the module zip file
2. Open Magisk Manager
3. Go to Modules tab
4. Click on Install from storage
5. Select the downloaded zip file
6. Reboot your device

## Usage
After installation, you can:

1. **Toggle Gaming Mode**:
   - Open Magisk Manager
   - Go to Modules tab
   - Find the Gaming Performance Booster module
   - Tap the Action button to toggle between Gaming Mode and Normal Mode

2. **Check Status**:
   ```
   su
   gaming_boost
   ```

## Best Practices
- Only activate Gaming Mode when playing games
- Return to Normal Mode when not gaming to save battery
- Monitor device temperature during extended gaming sessions
- For maximum stability, don't enable Gaming Mode during important calls or tasks
- If you experience any issues, tap the Action button to return to Normal Mode

## Compatibility
- Works on all devices running Android 10 and above
- Compatible with Magisk v20.4+
- Tested on various device manufacturers
- Automatically adapts to your device's hardware capabilities

## Warning
While this module includes safety measures to prevent issues, use the Gaming Mode with caution:
- Extended use may cause device warming
- Battery drain will be faster in Gaming Mode
- If any instability occurs, switch back to Normal Mode immediately
- The module will automatically disable itself if bootloop is detected

## Credits
- Magisk by topjohnwu

## License
This module is open source and available under the MIT License. 