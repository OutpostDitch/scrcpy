# Scrcpy - Windows 10 & 11
[![PowerShell Setup Button](./imgs/button.png)](https://outpostditch.github.io/scrcpy/)
## Introduction

Scrcpy is a powerful application designed to display and control Android devices from a Windows computer. It addresses the need for users to manage their mobile experience conveniently from their desktop, allowing for a seamless interaction without the need for physical device handling. Whether you're a developer testing applications or a user wanting to project your phone screen, Scrcpy offers a practical solution.

This tool enables real-time screen mirroring and control of Android devices over USB or Wi-Fi, providing features such as high-quality video streaming and low latency. Users can easily interact with their devices using keyboard and mouse inputs, making it ideal for presentations, app testing, and more.

Scrcpy stands out due to its performance and ease of use. It is particularly valuable for developers who want to test their applications on different devices without the need for constant physical access. Furthermore, educators can use Scrcpy to demonstrate mobile applications in a classroom setting, enhancing the learning experience. By eliminating the need to switch between devices, users can maintain focus and improve productivity.

---

## System Requirements

| Requirement           | Details                                  |
|----------------------|------------------------------------------|
| Supported Windows OS | Windows 10, Windows 11                  |
| Architecture         | x64                                      |
| Processor            | Not specified, but a modern multi-core processor is recommended for optimal performance |
| RAM                  | Not specified, but at least 4 GB is recommended for smoother operation |
| Storage              | Not specified, but ensure enough space for the application and any temporary files |
| Permissions          | Administrator permissions may be required for certain operations |
| Internet Connection   | Not required for local usage             |
| Dependencies         | Not specified, but having the latest ADB (Android Debug Bridge) installed is advisable |

**Note**: While specific hardware requirements are not outlined, it is advisable to use a modern computer setup to take full advantage of Scrcpy's capabilities, especially when dealing with high-resolution displays and multiple connected devices.

---

## Features

- **Real-time Screen Mirroring**: View your Android device's screen on your Windows PC with minimal delay, enhancing your interaction experience. This feature is particularly beneficial for users who need to demonstrate app functionality or conduct software training.

- **Control from PC**: Use your keyboard and mouse to navigate and control your Android device, making it easier to manage apps and settings. This eliminates the hassle of constantly switching between devices and allows for a more fluid workflow.

- **USB and Wi-Fi Connectivity**: Connect your Android device via USB or Wi-Fi, providing flexibility in how you choose to interact with your device. USB connections typically offer lower latency and better performance, while Wi-Fi connections allow for greater mobility.

- **High-Quality Streaming**: Enjoy a clear and fluid display of your device's screen, supporting resolutions up to 1920x1080 (or higher) at 30-60 FPS. This feature is essential for users who want to capture high-quality content or conduct detailed demonstrations.

- **File Transfer Capabilities**: Easily drag and drop files between your Android device and PC, simplifying the transfer of documents, images, and other media. This feature streamlines workflows, especially for users who frequently move files between devices.

- **Recording Feature**: Capture your screen activity directly from your Android device, perfect for creating tutorials or documenting app behavior. This is particularly useful for developers and content creators who need to produce instructional videos.

- **Customizable Settings**: Adjust settings for video quality and latency according to your specific needs, ensuring optimal performance based on your hardware capabilities. Users can tailor their experience to match the demands of their specific applications.

- **Multi-device Support**: Connect multiple Android devices simultaneously, allowing for multitasking and comparisons between different devices. This feature is invaluable for developers testing apps across various devices or for educators managing multiple student devices.

- **Open Source**: As an open-source project, Scrcpy is free to use and modify, encouraging community contributions and transparency. This open model fosters innovation and allows users to benefit from improvements made by the global developer community.

- **Cross-platform Compatibility**: While optimized for Windows, Scrcpy can also be used on other operating systems, making it versatile for developers and users. This capability allows for a broader audience and ensures that users can access the application regardless of their preferred OS.

---

## How It Works

1. **Install Scrcpy**: Download and install Scrcpy on your Windows PC. Ensure your Android device has USB debugging enabled. This step is crucial, as it allows your Windows PC to communicate effectively with your Android device.

2. **Connect Your Device**: Use a USB cable or connect via Wi-Fi to link your Android device with your computer. For USB connections, ensure that you use a quality cable to minimize latency and ensure stable connectivity.

3. **Launch the Application**: Open Scrcpy on your PC. The application will automatically detect your connected Android device. If you have multiple devices connected, you can select which one you want to control.

4. **Interact and Control**: Begin controlling your Android device from your Windows PC. You can mirror your screen, navigate apps, and perform tasks directly from your keyboard and mouse. All interactions, including gestures and taps, are replicated on the Android device in real-time.

5. **Utilize Additional Features**: Explore the various features Scrcpy offers, such as screen recording and file transfers. You can also access customizable settings to optimize performance based on your specific use case or hardware.

6. **Disconnect Safely**: When finished, ensure to safely disconnect your device. For USB connections, you can simply unplug the cable or close the Scrcpy application. For Wi-Fi connections, disconnect through the application settings.

---

## Compatibility

**Operating Systems and Architecture**  
Scrcpy is compatible with Windows 10 and Windows 11, specifically for x64 architecture. Users on other operating systems, such as macOS and Linux, can also use Scrcpy, although certain features may require additional configurations.

**Hardware Requirements**  
While specific hardware requirements are not detailed, a modern processor and sufficient RAM are recommended for optimal performance. A multi-core processor is ideal for ensuring smooth operation, especially when mirroring high-resolution displays.

**Runtime Dependencies**  
Scrcpy does not specify particular runtime dependencies. However, it is advisable to have the latest version of ADB (Android Debug Bridge) installed for full functionality. ADB is essential for enabling communication between your Android device and your PC.

**Limitations and Notes**  
Scrcpy may not function correctly with older Android devices or versions that do not support USB debugging. Performance may vary based on the hardware capabilities of the Windows machine. Additionally, certain features, such as high-resolution streaming, may be limited by the processing power of the computer being used.

It is also important to note that some security settings on your Android device may restrict the functionality of Scrcpy. If you encounter issues, check your device's security settings and ensure that the necessary permissions are granted.

---

## FAQ

### What is Scrcpy used for?
Scrcpy is primarily used for displaying and controlling Android devices from a Windows PC. It allows users to interact with their mobile devices without needing to handle them physically, making it ideal for presentations, app testing, and media management.

### How do I install Scrcpy on Windows?
To install Scrcpy, download the appropriate version for Windows from the official repository. Extract the files to a desired location, enable USB debugging on your Android device, and connect it to your PC via USB or Wi-Fi. Launch the application to start using it.

### Is Scrcpy compatible with all Android devices?
While Scrcpy works with most Android devices, it requires USB debugging to be enabled. Some older devices may not support this feature, which could limit functionality. Always check your device settings if you encounter issues.

### Can I use Scrcpy without an internet connection?
Yes, Scrcpy can be used entirely offline, as it establishes a direct connection between your Android device and your Windows PC through USB or local Wi-Fi.

### What should I do if Scrcpy is not detecting my device?
If Scrcpy does not detect your device, ensure that USB debugging is enabled on your Android device. Additionally, check that the necessary drivers are installed for your device on your Windows PC. Restarting both devices and reconnecting may also help resolve detection issues. If the problem persists, consider using a different USB port or cable, as hardware issues can sometimes be the cause.

---

## Disclaimer

Details about Scrcpy may vary based on version and system configuration. Users are advised to back up important data before making changes or utilizing the software to avoid potential data loss. Additionally, while Scrcpy is a reliable tool, users should proceed with caution when modifying device settings and ensure that they are aware of the implications of enabling USB debugging on their Android devices.

---

## License

The license for Scrcpy is not explicitly stated in the available documentation. Users should consult the license distributed with the software or the vendor's official terms for specific licensing information. As an open-source project, Scrcpy encourages collaboration and contributions from the community, fostering an environment of continuous improvement and innovation. Users are encouraged to understand the terms of the license and abide by them when using or modifying the software.
