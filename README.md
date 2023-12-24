# NeatInfo

## What is NeatInfo?
NeatInfo is a Conky theme crafted exclusively for Xfce environments, offering a clean and comprehensive display of system information on your desktop. Beyond its aesthetic appeal, NeatInfo introduces a range of addons that enhance its functionality:
![2023-12-21_20-37](https://github.com/somen3/NeatInfo/assets/92948254/b1bd6d87-f3b9-48e5-8928-5b6301aae23a)

### Addons:
- **Note and Todos**: Seamlessly jot down notes and manage todos directly within Conky.
- **Weather Updates**: Stay informed about weather conditions right from your desktop.
- **System Info**: Access comprehensive system information directly through Conky.
- **RSSFeeds**: Fetch content from your favorite news sites.

## Prerequisites

Before using this Conky theme, ensure you have the following dependencies installed:

- **xmlstarlet**: Used for XML document processing.
- **jq**: A lightweight and flexible command-line JSON processor.
- **ansiweather**: Provides weather information in the terminal.

## Installation
1. **Download NeatInfo**: Acquire the theme files.
2. **Extract the Files**: Unzip the downloaded files.
3. **Run with Conky Manager**:
   - Launch Conky Manager.
   - Click on "Add" and navigate to the NeatInfo theme folder (`~/.conky/`).
   - Select the NeatInfo configuration file to activate the Conky theme.

4. **Run `create_shortcuts.sh`**:
   - Open Terminal.
   - Navigate to the NeatInfo directory.
   - Execute `chmod +x create_shortcuts.sh` to grant execution permissions.
   - Run `./create_shortcuts.sh` to add essential application shortcuts to your desktop environment.

## Usage

- **Note**: Super + N
- **Clear Conky Note**: Super + C
- **Weather**: Super + W
- **RSS Feeds**: Super + R (You can add your favorite rssfeed url to ~/.conky/NeatInfo/addon/rssfeeds.txt)
- **System Info**: Super + S




