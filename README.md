# ranger-kdeconnect
A plugin for the [ranger](https://github.com/ranger/ranger) file manager to send files through [KDE Connect](https://github.com/KDE/kdeconnect-kde).

### Dependencies
- `kdeconnect-cli`
    - [How to install](https://github.com/KDE/kdeconnect-kde#how-to-install)
### Installation
Copy `kdeconnect_send.py` to `${XDG_CONFIG_HOME}/ranger/plugins` and restart ranger.

### Usage
- `:kdeconnect_send`: Sends the selected files to the your first connected device. 
    - __Note__: Directories are skipped.
