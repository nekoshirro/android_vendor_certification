# Android Vendor Certification
---

In recent times, Google has become increasingly strict with Play Integrity, and fingerprint is one of the key factors that determine whether a device passes the Play Integrity test. This test is essential for ensuring the authenticity and security of apps on Android devices. Play Integrity evaluates the device's integrity to determine if it has been tampered with or is running an uncertified version of Android. By having a valid fingerprint that matches Google's expectations, devices are more likely to pass this test, ensuring compatibility with the Google Play Store and apps that rely on Google’s security mechanisms.

## How it works

This method works by patching the `gms_certified_props.json` file with fingerprints from Google Pixel devices. Typically, these fingerprints are accepted because Google uses them as part of the certification process. In most cases, stock fingerprints from OEM ROMs (such as Xiaomi or other manufacturers) can also work fine as long as the device has a valid keybox. The keybox ensures the authenticity of the fingerprint and increases the chances of passing the Play Integrity test.

## Credits

- This project is licensed under the GPL License.
- Based on work by MT (Author/Contributor).
- Includes components licensed under the Apache License.
- Forked from Derpfest-AOSP.
