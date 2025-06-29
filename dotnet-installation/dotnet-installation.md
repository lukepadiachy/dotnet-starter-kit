
# Installing .NET on Windows, Linux, and macOS

Welcome! This guide will help you install .NET on your machine—Windows, Linux, or macOS. For the most accurate and up-to-date instructions, always refer to the official Microsoft documentation linked below. This guide will show you how to:
- Find the latest .NET version
- Check if your system meets the requirements
- Install .NET on your operating system
- Verify your installation

---

## 1. Find the Latest .NET Version

The .NET team regularly releases new versions. To ensure you install the latest stable version:
- Visit the [official .NET download page](https://dotnet.microsoft.com/download/dotnet).
- The page will highlight the latest version at the top (for example, ".NET 9" or newer).
- Choose the SDK for your platform (Windows, Linux, or macOS).

**Tip:** Always use the version marked as "Recommended" or "LTS" (Long Term Support) unless you have a specific need for a preview or older version.

---

## 2. Check System Requirements

Before installing, make sure your machine meets the requirements for the .NET version you want to install. You can find detailed requirements for each OS here:
- [Windows requirements](https://learn.microsoft.com/en-us/dotnet/core/install/windows#supported-versions)
- [macOS requirements](https://learn.microsoft.com/en-us/dotnet/core/install/macos#supported-versions)
- [Linux requirements](https://learn.microsoft.com/en-us/dotnet/core/install/linux#supported-versions)

**How to check your system:**
- **Windows:**
  - Open PowerShell and run:
    ```powershell
    systeminfo
    ```
    This will show your OS version, architecture, and more.
- **macOS:**
  - Open Terminal and run:
    ```bash
    sw_vers
    uname -m
    ```
    This will show your macOS version and CPU architecture.
- **Linux:**
  - Open Terminal and run:
    ```bash
    uname -a
    lsb_release -a  # (if available)
    ```
    This will show your distribution, version, and architecture.

If your OS or hardware is not listed in the official requirements, .NET may not be supported.

---

## 3. Install .NET

Follow the instructions for your operating system below. Always use the links to the official docs for the most current steps and troubleshooting.

### Windows

**Official guide:** [Install .NET on Windows](https://learn.microsoft.com/en-us/dotnet/core/install/windows)

**Quick steps:**
1. Go to the [official .NET download page](https://dotnet.microsoft.com/download/dotnet).
2. Download the SDK Installer for Windows (choose x64 if unsure).
3. Run the installer and follow the prompts.
4. After installation, open PowerShell and run:
   ```powershell
   dotnet --version
   ```
   This should display the installed .NET version.

**Other install options:**
- [Install with WinGet](https://learn.microsoft.com/en-us/dotnet/core/install/windows#install-with-windows-package-manager-winget)
- [Install with PowerShell script](https://learn.microsoft.com/en-us/dotnet/core/install/windows#install-with-powershell)

### macOS

**Official guide:** [Install .NET on macOS](https://learn.microsoft.com/en-us/dotnet/core/install/macos)

**Quick steps:**
1. Go to the [official .NET download page](https://dotnet.microsoft.com/download/dotnet).
2. Download the SDK Installer for macOS (choose Arm64 for Apple Silicon, x64 for Intel).
3. Open the downloaded file and follow the prompts.
4. After installation, open Terminal and run:
   ```bash
   dotnet --version
   ```

**Other install options:**
- [Install with script](https://learn.microsoft.com/en-us/dotnet/core/install/macos#install-net-with-a-script)

### Linux

**Official guide:** [Install .NET on Linux](https://learn.microsoft.com/en-us/dotnet/core/install/linux)

1. Go to the [official Linux install guide](https://learn.microsoft.com/en-us/dotnet/core/install/linux) for your distribution (Ubuntu, Fedora, etc.).
2. Follow the step-by-step instructions for your OS.

---

## 4. Verify Your Installation

After installation, open your terminal (PowerShell, Command Prompt, or Terminal) and run:
```shell
dotnet --info
```
This will display detailed information about your .NET installation.

---

## 5. Troubleshooting & Support

- If you encounter issues, check the [official troubleshooting guide](https://learn.microsoft.com/en-us/dotnet/core/install/troubleshoot).
- For supported versions and end-of-life dates, see the [.NET support policy](https://dotnet.microsoft.com/platform/support/policy/dotnet-core).

---

For always up-to-date instructions, visit the [official .NET documentation](https://learn.microsoft.com/en-us/dotnet/core/install/).