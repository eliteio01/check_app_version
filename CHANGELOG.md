## 1.0.1


# Changelog

### 1.0.1 (2025-04-23)

*   **Initial release** of the `app_update_monitor` package.

*   Allows comparison of the current app version with the versions available in the Apple App Store (iOS) and Google Play Store (Android).

*   Provides functionality to fetch the current version of the app installed on the device and compare it with the latest versions available in both stores.

*   Supports region-specific version info through optional country code parameter.

*   Easy integration with simple API methods: `checkVersion()` and `_shouldUpdate()`.
