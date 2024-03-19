# Welcome to GrapheneOS: A Complete Guide for New Users

**GrapheneOS** is a privacy-focused, security-hardened mobile operating system based on the [Android Open Source Project (AOSP)](https://source.android.com). It prioritizes user control and data protection, offering a unique experience for those seeking enhanced digital autonomy. This guide is a one-stop resource for new users, covering everything from device purchase to advanced usage.

## Why GrapheneOS is the Best Choice for a New Phone
GrapheneOS is the only custom Android-based operating system you should buy a new phone for. It provides substantial security hardening and privacy enhancements over the stock operating system from Google, such as:
- Hardened memory allocator
- Network and sensor permissions
- Full firmware updates and signed builds, supporting verified boot
- Optional Sandboxed Google Play, allowing you to use Google Play Services while controlling their permissions and access
- Support for most Google Play Services features, including push notifications, In-app Billing API, Google Play Games, Play Asset Delivery, and FIDO2
- Advanced Protection Program features, except for Play Protect and restricted app installation
- Storage Scopes feature, allowing you to force apps that request broad storage access permission to function with scoped storage

For a comprehensive list of GrapheneOS features and improvements over AOSP, please refer to the [official features page](https://grapheneos.org/features).

Google Pixel phones are the **only** devices that meet GrapheneOS's [hardware security requirements](https://grapheneos.org/faq#device-support).

Even prominent privacy experts like Edward Snowden, the well-known NSA whistleblower and privacy advocate, use GrapheneOS as their mobile operating system of choice. 

![image](https://github.com/iAnonymous3000/awesome-grapheneos-guide/assets/32236127/78571e0b-9e81-451d-83ef-02269aa729fd)


## GrapheneOS vs. Other Android ROMs

While GrapheneOS is our recommended choice for a privacy-focused and secure Android experience, it's worth comparing it to other popular Android ROMs to understand its unique advantages. The following table provides a detailed comparison of GrapheneOS with other ROMs such as DivestOS, CalyxOS, IodéOS, /e/, LineageOS, and stock Android:


| Feature/Aspect | GrapheneOS | DivestOS | CalyxOS | IodéOS | /e/ | LineageOS | Stock Android |
|----------------|------------|----------|---------|--------|-----|------------|---------------|
| Based on | AOSP | AOSP fork | AOSP | AOSP fork | AOSP fork | AOSP | AOSP |
| Free and open source (FOSS)? | Yes | Yes | Yes | Yes | Yes | Yes | No |
| Proprietary code removal | High | High | Medium | Low | Low | Low | No |
| Sandboxed Google Play? | Optional | No | No | No | No | No | No |
| Storage scopes | Yes | No | No | No | No | No | No |
| Verified boot | Yes | Partial | Partial | Partial | Partial | No | Partial |
| Hardened allocator | Yes | Yes | No | No | No | No | No |
| Hardened kernel | Yes | Yes | No | No | No | No | No |
| Security update speed | Fastest | Fast | Moderate | Slow | Slow | Moderate | Varies by vendor |
| Long-term support | 5 years | Several years | 1-3 years | Several years | Several years | Several years | No |

*Note: The table above is a simplified version. To get the latest and detailed information, check out the [complete comparison table](https://eylenburg.github.io/android_comparison.htm) by [@eylenburg](https://github.com/eylenburg)*

As evident from the comparison, GrapheneOS stands out in terms of its strong focus on privacy, security, and freedom. It is based on AOSP, is fully open-source, and has been extensively deblobbed. GrapheneOS also offers unique features such as per-app network controls, storage and contact scopes, and advanced security hardening.

While other ROMs like DivestOS and CalyxOS also prioritize privacy and security, they may not offer the same level of granular control and advanced security features as GrapheneOS. LineageOS and /e/ are more focused on providing an alternative to stock Android with additional customization options, but they may not be as hardened as GrapheneOS.

Ultimately, the choice of ROM depends on your specific needs and priorities. However, if your primary concern is privacy and security, GrapheneOS is the clear winner among the compared ROMs.

## Purchasing a Mobile Phone

- **Selecting a Device:** Purchase the latest Google Pixel phone (preferably new; try to avoid used phone as it might be tampered with) with cash from a local store. GrapheneOS currently only supports Google Pixel devices due to their strong security features and proper alternate OS support. Avoid devices from mobile carriers, as they may lock the bootloader and prevent you from installing an alternative OS.
- **Transaction Anonymity:** Ensure the transaction remains anonymous to prevent the phone's IMEI from being linked to your identity.

## Configuring Your Device

- **Initial Configuration**: Consider your threat model and privacy needs when deciding whether to use a public Wi-Fi network for initial setup.
- **Accessories:** Invest in a protective case and privacy screen protector for the Google Pixel Phone.

## Installing GrapheneOS

- **Compatibility Check:** Ensure your Pixel device is compatible at [GrapheneOS FAQ](https://grapheneos.org/faq).
- **Backup Data:** Backup existing data before installation.
- **Installation Methods:** Use the [Web Installer](https://grapheneos.org/install/web) for the easiest and most foolproof installation. The [CLI Installer](https://grapheneos.org/install/cli) is available for advanced users.

## Initial Setup

After installing GrapheneOS, follow these steps to set up your device:

1. Press the power button to boot into GrapheneOS.

2. Select your preferred language and region.

3. Set up a strong PIN code or password for your device. Use a 6-digit random PIN if relying on the secure element throttling or a ~90-bit entropy password if not relying on the secure element.

4. Connect to a Wi-Fi network. If possible, use a trusted and secure network, such as your home Wi-Fi, for the initial setup.

5. GrapheneOS will be up-to-date if you install the latest stable release. No immediate update is necessary.

6. Review and adjust privacy settings:
   - Go to Settings > Privacy.
   - Review each option and adjust settings according to your preferences.

7. Set up a secure lock screen:
   - Go to Settings > Security > Screen lock.
   - Choose a strong PIN or password. Pattern unlock is not available in GrapheneOS due to security concerns.
   - Note on Lockdown mode:

     Lockdown mode is a feature that temporarily disables biometric unlocking, fingerprint unlocking, and notifications on the lock screen. This can be particularly useful in situations where you might be compelled to unlock your device against your will, such as during a border crossing or police encounter. When Lockdown mode is activated, your device can only be unlocked with your PIN, pattern, or password.

     Enabling Lockdown mode is not necessary for all users and depends on your specific security needs and threat model. Lockdown mode is always available on GrapheneOS and does not require any additional setup. To activate Lockdown mode, simply press and hold the power button and then tap the "Lockdown" option that appears on the power menu.

     Keep in mind that Lockdown mode is not a setting that you enable permanently, but rather a one-time action that you can use whenever you need an extra layer of security. If you choose to use Lockdown mode, familiarize yourself with activating it quickly in case you ever need to use it under pressure.

8. Disable OEM unlocking:
   - Go to Settings > About phone > Tap "Build number" until developer mode is enabled.
   - Go to Settings > System > Developer options.
   - Disable the "OEM unlocking" toggle.
   - Restart your device to enable the device protection feature.

9. Automatic updates are enabled by default. You can set constraints such as network type, charging status, and battery percentage in the update settings.

10. Set up a secure backup method:
    - Go to Settings > System > Backup.
    - Choose a secure backup option, such as Seedvault or an encrypted cloud storage service.

11. Install apps from trusted sources based on your individual needs. 

12. Configure any additional security or privacy features according to your needs, such as app permissions, network controls, or sensor controls. Do NOT modify permissions for system apps.

Following these steps will give you a more secure and privacy-focused initial setup for your GrapheneOS device. Remember to regularly review and update your settings and apps to maintain the highest level of security and privacy.

## Migration Tips

When transitioning to GrapheneOS from another operating system, consider the following tips for a smooth migration:

- **Backup Your Data**: Ensure important data such as contacts, photos, and documents are backed up to a secure location.
- **Transfer Securely**: Use encrypted methods or direct connections to transfer data to your new GrapheneOS device.
- **Review Apps**: GrapheneOS maintains excellent app compatibility, especially when using Sandboxed Google Play. Most apps should work without issues on GrapheneOS. However, if you rely on apps with advanced functionality or specific security requirements, it's always a good idea to check their compatibility beforehand. In the rare case that an app is incompatible, explore secure alternatives available through the Play Store or F-Droid.

## Battery Life and Performance

- **Battery Life:** GrapheneOS has better battery life than the stock OS by default. When using Sandboxed Google Play, battery life is expected to be on par with the stock OS.
- **Performance:** The device's performance should remain smooth and responsive, with minimal impact from GrapheneOS's security measures.

## App Compatibility and Alternatives

- **Google Play Store Apps:** GrapheneOS maintains app compatibility through the optional installation of Sandboxed Google Play. Most apps should work without issues. Consider using alternative apps from F-Droid or the Aurora Store.
- **MicroG** is not a suitable alternative for GrapheneOS users, as it requires privileged installation to function properly.

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

For the most up-to-date information on troubleshooting app compatibility issues on GrapheneOS, please refer to the [official GrapheneOS discussion thread](https://discuss.grapheneos.org/d/8330-app-compatibility-with-grapheneos).

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

- **Warranty:** Installing GrapheneOS on a Google Pixel device does not void the warranty, as it is fully supported and expected.
- **Jurisdiction:** GrapheneOS is not known to be banned in any jurisdiction.

## Advanced Usage

- **Community Contributions:** Engage in contributions through [GrapheneOS GitHub](https://github.com/GrapheneOS).
- **Self-building GrapheneOS:** Build the OS yourself following the [Building Guide](https://grapheneos.org/build).
- **[Community Engagement](https://grapheneos.org/contact#community):** Participate in forums and chat channels for support and discussions.

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
- [Curated opensource apps for privacy-centric GrapheneOS users](https://alternativeto.net/list/35462/grapheneos-appverse/)
- [Banking Applications Compatibility with GrapheneOS](https://privsec.dev/posts/android/banking-applications-compatibility-with-grapheneos/)

## Why GrapheneOS Currently Supports Only Google Pixel Devices
- GrapheneOS requires devices to have strong security features and proper alternate OS support, which most Android OEMs, including Samsung, do not provide.
- Pixels are nearly the only devices providing both strong security and proper alternate OS support.
- GrapheneOS will [support more devices in the future](https://grapheneos.org/faq#future-devices) when there are other devices meeting their basic security requirements, but they are not willing to give up extremely important security features.

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
