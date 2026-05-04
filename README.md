# Ubuntu Experience

A web-based interactive demo of the Ubuntu Touch mobile operating system. Try Ubuntu Touch without flashing your phone!

## Try Ubuntu Touch Without Flashing

There are several ways to experience Ubuntu Touch without modifying your device:

### 1. This Web Demo
This interactive web-based demo simulates the Ubuntu Touch experience directly in your browser. It features:
- Lock screen with time and notifications
- App launcher with grid of apps
- System settings
- Weather app
- Music player
- Terminal with commands
- And more!

**No installation required** - just open in your browser.

### 2. Anbox for Android (Android Only)
Anbox runs Ubuntu Touch apps on a standard Android device without flashing:

```bash
# Install Anbox from Google Play or F-Droid
# Then enable Ubuntu Touch mode in Anbox settings
```

### 3. Ubuntu Touch Emulator (Virtual Machine)
The UBports team provides a virtual machine image:
- Download from: https://docs.ubports.com/en/latest/guides/virtualbox.html
- Requires VirtualBox
- Full Ubuntu Touch desktop experience

### 4. WebDFU (Experimental)
Some devices can run Ubuntu Touch in a chroot without flashing:
- https://webdfu.fuerstenau.io/
- Currently supports limited devices

### 5. pine64.org Community Images
The PinePhone and PineTab have community-supported images:
- Visit https://forum.pine64.org/ for the latest releases
- Run from SD card without affecting main OS

## Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Supported Devices (for actual installation)

If you decide to flash Ubuntu Touch to a device, these are officially supported:
- **OnePlus One** - Official
- **Fairphone 2** - Official
- **Google Nexus 5** - Official
- **LG Nexus 4** - Official
- **Bq Aquaris E5** - Official
- **PinePhone** - Community
- **PineTab** - Community

## Learn More

- [UBports Official Site](https://ubports.com)
- [Ubuntu Touch Documentation](https://docs.ubports.com)
- [UBports Forum](https://forum.ubports.com)
- [OpenStore](https://open-store.io) - App store for Ubuntu Touch

## License

MIT