# Building Tongram for iOS

## Prerequisites

- macOS 14+ (Sonoma or later)
- Xcode 15+
- Python 3
- CocoaPods or Swift Package Manager

## Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/TONGRAM/tongram-ai-ios.git
   cd tongram-ai-ios
   ```

2. Obtain API credentials:
   - Register at https://my.telegram.org/apps
   - Get `api_id` and `api_hash`
   - Place in the appropriate config file

3. Install dependencies:
   ```bash
   # If using CocoaPods
   pod install
   ```

4. Open in Xcode:
   ```bash
   open Tongram.xcworkspace
   ```

5. Configure signing:
   - Set your development team in Xcode
   - Update bundle identifier to `app.tongram.messenger`

6. Build and run on device or simulator

## Notes

- Requires Apple Developer account for device deployment
- First build may take 20-40 minutes
- Universal app (iPhone + iPad supported)
