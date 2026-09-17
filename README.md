# Taskbar Clock Customization — mzihadul Fork

A community-maintained fork of **Taskbar Clock Customization** by [m417z](https://github.com/m417z), with additional taskbar status indicators and other personal modifications.

> **Important:** This project is an independent fork. It is not the original `Taskbar Clock Customization` project and is not presented as an official Windhawk or m417z release.

## Original Project

This fork is based on:

- **Original project:** Taskbar Clock Customization
- **Original author:** m417z
- **Original source:** https://github.com/ramensoftware/windhawk-mods/blob/main/mods/taskbar-clock-customization.wh.cpp
- **Original development repository:** https://github.com/m417z/my-windhawk-mods
- **License:** GNU General Public License v3.0

The original source and attribution notices have been retained in the modified source.

## What this fork adds

The current fork adds the following taskbar patterns/features to the original mod:

### `%volume%`

Displays the current system audio volume with an icon.

- Shows a speaker icon during normal operation.
- Shows a muted icon when audio is muted.
- When the volume or mute state changes, the percentage is temporarily displayed.
- The percentage display automatically hides after approximately 3 seconds.

### `%mic%`

Displays a microphone-in-use indicator.

- Shows `🎙️` while Windows reports that a microphone is actively being used.
- Displays nothing when the microphone is not in use.

These additions allow the new patterns to be used anywhere the original mod supports formatting patterns, such as the taskbar clock lines and tooltip.

## Available patterns

In addition to the patterns provided by the original project, this fork adds:

| Pattern | Description |
|---|---|
| `%volume%` | Current system volume icon; temporarily shows the volume percentage when the volume/mute state changes. |
| `%mic%` | Shows a microphone indicator when Windows reports that the microphone is actively in use. |

The original project provides many other patterns for time, date, weather, system performance, media information, and more. See the original source for the complete list.

## Example

You can combine the new patterns with the existing ones. For example:

```text
%time% | 🔊 %volume% | %mic%
```

The exact appearance depends on your Windows taskbar, font, and Windhawk settings.

## Installation

### Using Windhawk

1. Install [Windhawk](https://windhawk.net/).
2. Open Windhawk.
3. Create/open a custom mod in the Windhawk mod editor.
4. Copy the contents of `taskbar-clock-customization-fork-v10.wh.cpp` into the editor.
5. Compile/apply the mod.
6. Configure the taskbar clock patterns in the mod settings.

Because this fork uses a different mod ID from the original, it is intended to be treated as a separate mod.

## Compatibility

The original project supports:

- Windows 10 64-bit
- Windows 11

Compatibility can vary depending on the Windows version/build and other taskbar customization software.

## Credits

### Original work

**Taskbar Clock Customization**  
Copyright/author: **m417z**

Original repository:

https://github.com/ramensoftware/windhawk-mods

Original source:

https://github.com/ramensoftware/windhawk-mods/blob/main/mods/taskbar-clock-customization.wh.cpp

### Fork

Modifications and maintenance:

**mzihadul**

Repository:

https://github.com/mzihadul/taskbar-clock-customization-fork

## License

This project is distributed under the **GNU General Public License v3.0 (GPL-3.0)**, consistent with the license of the original work.

See [`LICENSE`](./LICENSE) for the complete license text.

## Disclaimer

This is an independent community fork. Windows, Windhawk, and other referenced software/projects remain the property of their respective owners.

The fork is provided as-is. Use it at your own risk and make sure you understand the changes before applying the mod.
