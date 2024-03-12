# Welcome to GrapheneOS: A Complete Guide for New Users

**GrapheneOS** is a privacy-focused, security-hardened mobile operating system based on Android. It prioritizes user control and data protection, offering a unique experience for those seeking enhanced digital autonomy. This guide is a one-stop resource for new users, covering everything from device purchase to advanced usage.

## Why GrapheneOS is the Best Choice for a New Phone
GrapheneOS is the only custom Android-based operating system you should buy a new phone for. It provides additional security hardening and privacy improvements over the stock operating system from Google, such as:
- Hardened memory allocator
- Network and sensor permissions
- Full firmware updates and signed builds, supporting verified boot
- Sandboxed Google Play, allowing you to use Google Play Services while controlling their permissions and access
- Support for most Google Play Services features, including push notifications, In-app Billing API, Google Play Games, Play Asset Delivery, and FIDO2
- Advanced Protection Program features, except for Play Protect and restricted app installation
- Storage Scopes feature, allowing you to force apps that request broad storage access permission to function with scoped storage

Google Pixel phones are the **only** devices that meet GrapheneOS's [hardware security requirements](https://grapheneos.org/faq#device-support).

Even prominent privacy experts like Edward Snowden, the well-known NSA whistleblower and privacy advocate, use GrapheneOS as their mobile operating system of choice. 

![image](https://github.com/iAnonymous3000/awesome-grapheneos-guide/assets/32236127/78571e0b-9e81-451d-83ef-02269aa729fd)


## GrapheneOS vs. Other Android ROMs

While GrapheneOS is our recommended choice for a privacy-focused and secure Android experience, it's worth comparing it to other popular Android ROMs to understand its unique advantages. The following table provides a detailed comparison of GrapheneOS with other ROMs such as DivestOS, CalyxOS, IodéOS, /e/, LineageOS, and stock Android:

| Feature/Aspect | GrapheneOS | DivestOS | CalyxOS | IodéOS | /e/ | LineageOS | Stock Android |
|---------------------------------|-------------------|-------------------|-------------------|-------------------|--------------------|--------------------|-------------------|
| Based on | AOSP | LineageOS | AOSP | LineageOS | LineageOS | AOSP | AOSP |
| Free and open source (FOSS)? | Yes | Yes | Yes | Yes | Yes | Yes | No |
| Deblobbed? | Yes, significantly| Yes, extensively | Yes, significantly| Yes, minimal | Yes, minimal | Yes, minimal | No |
| Network controls for apps | Direct/indirect | Direct/indirect | Direct only | Direct only | Direct only | Direct only | No |
| E2E-encrypted phone backups | Yes (Seedvault) | Yes (Seedvault) | Yes (Seedvault) | Yes (Seedvault) | Yes (Seedvault) | Yes (Seedvault) | Yes (Google login)|
| Android Auto compatible | Yes | No | No | No | No | No | Yes |
| Google Pay compatible | No | No | No | No | No | No | Yes |
| Implementation | GmsCompat | microG | microG | microG | microG | None/manual MicroG| Google Play Services|
| Sandboxed/unprivileged? | Yes | Yes | No | No | No | No | No |
| Storage scopes | Yes | No | No | No | No | No | No |
| Per-app sensor controls | Yes | Yes | No | No | No | No | No |
| Verified boot | Yes | Yes (excl. system app updates)| Yes (excl. system app updates) | Yes (excl. system app updates) | w/ test keys; excl. system app updates | No | Yes (excl. system app updates) |
| Hardened memory allocator? | Yes | Yes | No | No | No | No | No |
| Hardened kernel? | Yes, highest | Yes, high | No | No | No | No | No |
| Security update speed | <2 days | 1-3 weeks | ~1 week | ~1 month | ~2 months | 1-2 weeks | Depends on vendor |
| Number of Android versions supported | Usually 1 | 7 (incl. backports) | Usually 1 | Usually 1 | 2-3 | Usually 3 | Usually 3 |

*Note: The table above is a simplified version. Please refer to the full comparison table for more details.*

As evident from the comparison, GrapheneOS stands out in terms of its strong focus on privacy, security, and freedom. It is based on AOSP, is fully open-source, and has been extensively deblobbed. GrapheneOS also offers unique features such as per-app network controls, storage and contact scopes, and advanced security hardening.

While other ROMs like DivestOS and CalyxOS also prioritize privacy and security, they may not offer the same level of granular control and advanced security features as GrapheneOS. LineageOS and /e/ are more focused on providing an alternative to stock Android with additional customization options, but they may not be as hardened as GrapheneOS.

Ultimately, the choice of ROM depends on your specific needs and priorities. However, if your primary concern is privacy and security, GrapheneOS is the clear winner among the compared ROMs.

## Purchasing a Mobile Phone

- **Selecting a Device:** Purchase the latest Google Pixel phone (preferably new; try to avoid used phone as it might be tampered with) with cash from a local store. GrapheneOS currently only supports Google Pixel devices due to their strong security features and proper alternate OS support. Avoid mobile data service providers' models that lock the OEM.
- **Transaction Anonymity:** Ensure the transaction remains anonymous to prevent the phone's IMEI from being linked to your identity.

## Mobile Carrier Setup

- **Recommended Connectivity:** Consider a [Calyx hotspot](https://calyxinstitute.org/membership/internet) for anonymous and unthrottled connectivity.

The Calyx Institute offers unlimited mobile internet for members at various levels. The mobile hotspots from Calyx use the T-Mobile network when available and fall back to the Sprint network otherwise. Service is available in the US and Puerto Rico.

![Calyx_Hotspot](https://github.com/iAnonymous3000/awesome-grapheneos-guide/assets/32236127/9ce75003-d07c-455d-868e-ade23a97323c)

- **SIM Card:** Buy a pre-paid Mint Mobile (T-Mobile) SIM card with cash.
- **Payment Method:** Use a [privacy.com](https://privacy.com) card for payments.
- **Data Plan:** Opt for Mint Mobile's $15/month plan for unlimited 4G/5G data.

## Configuring Your Device

- **Initial Configuration:** Use a public Wi-Fi network for initial setup.
- **Accessories:** Invest in a protective case and privacy screen protector for the Google Pixel.

## Installing GrapheneOS

- **Compatibility Check:** Ensure your Pixel device is compatible at [GrapheneOS FAQ](https://grapheneos.org/faq).
- **Backup Data:** Backup existing data before installation.
- **Installation Methods:** Use the [Web Installer](https://grapheneos.org/install/web) or [CLI Installer](https://grapheneos.org/install/cli) for installation.

## Initial Setup

After installing GrapheneOS, follow these steps to set up your device:

1. Press the power button to boot into GrapheneOS.

2. Select your preferred language and region.

3. Set up a strong PIN code for your device. Consider using a long, alphanumeric passphrase for enhanced security.

4. Connect to a Wi-Fi network. If possible, use a trusted and secure network, such as your home Wi-Fi, for the initial setup.

5. Update GrapheneOS to the latest version:
   - Go to Settings > System > System update.
   - If an update is available, download and install it.

6. Review and adjust privacy settings:
   - Go to Settings > Privacy.
   - Review each option and adjust settings according to your preferences.

7. Set up a secure lock screen:
   - Go to Settings > Security > Screen lock.
   - Choose a strong PIN, pattern, or password.
   - Consider enabling "Lockdown" mode for additional security.

8. Disable OEM unlocking:
   - Go to Settings > About phone > Tap "Build number" until developer mode is enabled.
   - Go to Settings > System > Developer options.
   - Disable the "OEM unlocking" toggle.
   - Restart your device to enable the device protection feature.

9. Enable automatic updates:
   - Go to Settings > System > System update > Auto update system.
   - Select a preferred option for automatic updates (e.g., "Over Wi-Fi only").

10. Set up a secure backup method:
    - Go to Settings > System > Backup.
    - Choose a secure backup option, such as Seedvault or an encrypted cloud storage service.

11. Install essential apps from trusted sources, such as F-Droid or Aurora Store.

12. Configure any additional security or privacy features according to your needs, such as app permissions, network controls, or sensor controls.

Following these steps will give you a more secure and privacy-focused initial setup for your GrapheneOS device. Remember to regularly review and update your settings and apps to maintain the highest level of security and privacy.

## Unique Features of GrapheneOS

- **Sandboxing:** Restricts app access to data and other apps.
- **No Google Play Services:** Minimizes tracking.
- **Verified Boot:** Secures against unauthorized modifications.
- **Privacy-focused Apps:** Pre-installed apps designed for privacy.
- **Open Source:** Transparency and community-driven development.
- **Hardware Memory Tagging**: GrapheneOS is the first platform using ARM hardware memory tagging by default, providing stronger security against exploitation.

## Battery Life and Performance

- **Battery Life:** GrapheneOS may have a slight impact on battery life due to its enhanced security features.
- **Performance:** The device's performance should remain smooth and responsive, with minimal impact from GrapheneOS's security measures.

## App Compatibility and Alternatives

- **Google Play Store Apps:** Some apps may not work due to the absence of Google Play Services. Consider using alternative apps from F-Droid or the Aurora Store.
- **MicroG:** A free and open-source alternative to Google Play Services that can improve app compatibility.

## Profiles

GrapheneOS supports both User Profiles and Work Profiles. Understanding the differences between these two types of profiles is crucial before deciding which one is right for you.

### User Profiles

User Profiles are designed to be used by different individuals sharing a single Android device. Each user has their own application data and preferences, as well as a user interface that allows them to switch between users manually. Key points about User Profiles:

- Each user is intended for use by a separate person
- Users have their own app data and preferences
- Users can run in the background while another user is active
- The system manages shutting down users to conserve resources when necessary
- Secondary users can be added directly through the user interface or using the Device Administration program

### Work Profiles

Work Profiles, also known as managed profiles, are a collection of app data that shares some system-wide settings (e.g., Wi-Fi and Bluetooth). A Work Profile is a subset of a user's existence and is linked to it. Key points about Work Profiles:

- Work Profiles are managed by an IT administrator
- The functionality offered by a Work Profile is distinct from that of the user's primary profile
- This method allows businesses to manage the environment in which company-specific apps and data run on a user's device while still allowing users to utilize their personal apps and accounts
- Developers should follow standard app development guidelines to ensure their apps work reliably on devices with Work Profiles

It's important to note that profiles are always linked to a parent user, which is determined by the user who created the profile. Profiles are only valid for the duration of the individual who created them.

For more information on how to develop apps that work seamlessly with Work Profiles, refer to the [Android for Business documentation](https://developer.android.com/work).

To learn more about the differences between User Profiles and Work Profiles in GrapheneOS, watch this [video guide](https://youtu.be/20C0FD7mGDY?si=TsprE4i3kJlc3iZP).

### Troubleshooting App Compatibility

Some apps, particularly banking apps, may experience compatibility issues with GrapheneOS due to the enhanced security features. If you encounter problems with an app not working as expected, try the following workarounds:

1. **Native code debugging**: By default, native code debugging is enabled. If you disabled it, try enabling it again and launching the app.
   - Settings ➔ Security ➔ Enable native code debugging

2. **Exploit protection compatibility mode**: Enable the per-app exploit protection compatibility mode and launch the app. Note that this may reduce system security.
   - Settings ➔ Apps ➔ App ➔ Advanced ➔ Exploit protection compatibility mode

3. **Secure app spawning**: As a last resort for testing purposes only, you can temporarily disable secure app spawning, restart your device, and launch the app to see if this feature caused the compatibility issue. Remember to re-enable secure app spawning afterward.
   - Settings ➔ Security ➔ Enable secure app spawning

4. **Alternative frontend clients**: Some apps may refuse to work if they detect that they were not installed from the Play Store. In such cases, using Sandboxed Google Play with a throwaway account may help.

If none of the above workarounds solve the issue, try searching the GrapheneOS forum, issue tracker, or community for the specific app name to see if others have found a solution.

If you still can't find a solution, consider capturing a bug report to submit to the GrapheneOS team:

1. Enable Developer options by going to Settings ➔ About ➔ Device identifiers ➔ Build number and tapping "Build number" 7 times.
2. Capture a bug report by going to Settings ➔ System ➔ Developer options ➔ Bug Report ➔ Interactive report ➔ REPORT.
3. Open a new issue on the GrapheneOS issue tracker, provide a description, and submit the bug report capture zip privately.
4. Disable Developer options when done.

Please note that some apps may simply be incompatible with GrapheneOS due to their reliance on the stock OS or Google Play Services. In such cases, it's recommended to contact the app developers and share the GrapheneOS Attestation Compatibility Guide to encourage them to support GrapheneOS and other alternative operating systems.

## Privacy Settings

- **App Permissions:** Review and manage app permissions to ensure they only have access to necessary data and features.
- **Location Services:** Control which apps can access your location and when.
- **Network Access:** Manage which apps can access the internet and local network.

## Security Best Practices

- **Strong Passwords:** Use strong, unique passwords for all accounts.
- **Two-Factor Authentication:** Enable two-factor authentication whenever possible.
- **App Downloads:** Be cautious when downloading apps from unknown sources.

## Backup and Restore

- **Seedvault:** GrapheneOS includes Seedvault, a secure and private backup solution.
- **Limitations:** Some data, such as app data from non-compatible apps, may not be backed up.

## Hardware Security Features

- **Titan M Chip:** Google Pixel devices feature the Titan M security chip, which GrapheneOS leverages for enhanced security.

## Firmware Updates

- **Updating Firmware:** GrapheneOS provides firmware updates directly, ensuring timely security patches and improvements.
- **Importance:** Keep your device's firmware up to date to maintain optimal security.

## Banking Applications Compatibility

- **International Support:** Compatibility list for international banking apps.
- **User Contributions:** Users can contribute reports through [GitHub](https://github.com/PrivSec-dev/banking-apps-compat-report/issues/342).
- **Developer Encouragement:** GrapheneOS promotes support for the hardware attestation API.

## Legal Considerations

- **Warranty:** Installing GrapheneOS may void your device's warranty. Check your device's warranty terms and conditions.
- **Jurisdiction:** Be aware of any legal implications of using GrapheneOS in your jurisdiction.

## Advanced Usage

- **Community Contributions:** Engage in contributions through [GrapheneOS GitHub](https://github.com/GrapheneOS).
- **Self-building GrapheneOS:** Build the OS yourself following the [Building Guide](https://grapheneos.org/build).
- **Community Engagement:** Participate in forums and chat channels for support and discussions.

## Best Practices and Tips

- **Regular Updates:** Keep OS and apps updated.
- **Customization:** Customize within GrapheneOS's privacy and security framework.
- **App Selection:** Choose apps that align with privacy and security goals.

## Troubleshooting and Support

- **Troubleshooting Guide:** Check [GrapheneOS Troubleshooting](https://grapheneos.org/faq#troubleshooting) for common issues.
- **Community Support:** Engage with the community for help and guidance.

## Additional Resources

- **Official Website:** [GrapheneOS](https://grapheneos.org/)
- **Documentation:** Access detailed resources at [GrapheneOS Documentation](https://grapheneos.org/faq)
- **Community Forum:** Join discussions at [GrapheneOS Forum](https://discuss.grapheneos.org/)
- **Chat Channel:** Connect with the community via [GrapheneOS Chat](https://grapheneos.org/contact)
- [Comprehensive Comparison of Android ROMs](https://eylenburg.github.io/android_comparison.htm)
- [Curated opensource apps for privacy-centric GrapheneOS users](https://alternativeto.net/list/35462/grapheneos-appverse/)
- [Banking Applications Compatibility with GrapheneOS](https://privsec.dev/posts/android/banking-applications-compatibility-with-grapheneos/)

## Why GrapheneOS Currently Supports Only Google Pixel Devices
- GrapheneOS requires devices to have strong security features and proper alternate OS support, which most Android OEMs, including Samsung, do not provide.
- Pixels are nearly the only devices providing both strong security and proper alternate OS support.
- GrapheneOS will support more devices in the future when there are other devices meeting their basic security requirements, but they are not willing to give up extremely important security features.

## Future Plans and Roadmap

GrapheneOS has ambitious long-term plans to move beyond being a hardened fork of the Android Open Source Project. The key goals include:

- Moving away from relying on the Linux kernel as the core of the OS and foundation of the security model
- Transitioning towards a microkernel-based model with a Linux compatibility layer
- Adopting virtualization-based isolation to reinforce existing security boundaries

The roadmap can be broken down into several phases:

1. **Near-term enhancements**: Check the issue trackers for planned improvements and features. The majority of open issues are concrete and actionable.

2. **Hypervisor integration**: Deploy and integrate a hypervisor like Xen to leverage it for reinforcing existing security boundaries. Linux would run inside virtual machines at this stage.

3. **Sandbox reinforcement**: Replace Linux inside the sandboxes with a compatibility layer like gVisor, which would need to be ported to arm64 and given a new backend alongside the existing KVM backend.

4. **Phasing out Linux**: Over the long term (many years), Linux can be phased out completely, along with the usage of virtualization.

5. **Hardware and firmware security**: While currently limited to research and submitting suggestions and bug reports upstream, GrapheneOS aims to move into the hardware space in the long term.

GrapheneOS anticipates that many other projects will be interested in this kind of migration, so it won't be solely a GrapheneOS project. Having a hypervisor with verified boot intact will also provide a way to achieve some of the goals based on extensions to Trusted Execution Environment (TEE) functionality, even without having GrapheneOS-specific hardware.

For more details on the near-term roadmap, check out the GrapheneOS [issue trackers](https://grapheneos.org/contact#reporting-issues), where most of the open issues represent planned enhancements.

## Conclusion

GrapheneOS stands at the forefront of mobile privacy and security. This guide is designed to assist you in making the most of your GrapheneOS experience, from the initial device purchase to everyday use, including banking app compatibility and community engagement. While GrapheneOS currently only supports Google Pixel devices, they are open to supporting other devices in the future that meet their strict security requirements.

**Your feedback and contributions are essential to keep this guide comprehensive and current. We welcome you to the GrapheneOS community and wish you a secure digital journey!**
