# 🎨 icons8-download-cli - Batch Download Icons Easily

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/strale73/icons8-download-cli/releases)

## 🚀 Getting Started

This tool helps you download icons in bulk from Icons8.com. You can filter icons by style, making it simple to find exactly what you need for your project. Follow these steps to get started.

## 🔍 Features

- **Batch Downloading:** Download multiple icons at once to save time.
- **Style Filtering:** Choose specific styles to narrow down your downloads.
- **User-Friendly:** Designed for average users, no programming skills needed.
- **Cross-Platform:** Works on Windows, macOS, and Linux.
- **Lightweight Utility:** Quick installation and minimal resource usage.

## 🖥️ System Requirements

To use the icons8-download-cli tool, ensure your system meets the following requirements:

- **Operating System:** Windows 10 or higher, macOS 10.12 or higher, or any Linux distribution.
- **Python Version:** Python 3.6 or higher must be installed.
- **Internet Connection:** Required for accessing Icons8.com.

## 📦 Download & Install

Visit this page to download the latest release: [Download the latest release](https://github.com/strale73/icons8-download-cli/releases).

1. Click on the "Releases" link.
2. Find the most recent version.
3. Download the appropriate file for your operating system:
   - For Windows: `icons8-download-cli.exe`
   - For macOS: `icons8-download-cli.pkg`
   - For Linux: `icons8-download-cli.tar.gz`
4. Follow the installation instructions based on your operating system:

### 🖥️ For Windows:
- Double-click `icons8-download-cli.exe`.
- Follow the prompts in the installation wizard.

### 🍏 For macOS:
- Open the downloaded `.pkg` file.
- Follow the instructions in the installer.

### 🐧 For Linux:
- Extract the `.tar.gz` file using your terminal:
  ```bash
  tar -xvzf icons8-download-cli.tar.gz
  ```
- Navigate to the extracted folder and run the program:
  ```bash
  cd icons8-download-cli
  ./icons8-download-cli
  ```

## 🎯 Usage Instructions

Once installed, you can start using the tool to download icons. Here's how:

1. Open your command line interface (Command Prompt for Windows, Terminal for macOS/Linux).
2. Type the following command to download icons:
   ```
   icons8-download-cli --query "icon name" --style "style name"
   ```
   Replace "icon name" with the specific icon you want and "style name" with your desired style (e.g., flat, outline).

3. Hit Enter, and the tool will begin downloading the icons to your current directory.

### 📁 Output Directory

By default, the downloaded icons will appear in the same folder where you ran the command. You can specify a different directory using the `--output` option:

```
icons8-download-cli --query "icon name" --style "style name" --output "/path/to/directory"
```

## 📜 Command Options

Here’s a brief overview of the most useful command options:

- `--query <icon name>`: Specify the name of the icon you are looking to download.
- `--style <style name>`: Filter results by style (e.g., flat, outline).
- `--output <directory>`: Choose a folder for downloaded icons.
- `--help`: See all available commands and options.

## 👩‍💻 Support

If you encounter any issues, please visit our support page on GitHub. You can also ask questions in the Issues section. We are here to help you.

## 🔗 Additional Resources

- [Icons8 Official Website](https://icons8.com)
- [Python Official Website](https://www.python.org)

## 🙌 Thank You

Thank you for using icons8-download-cli. We hope it simplifies your icon downloading process!