# iOS Peek & Context Menu

An iOS-inspired message peek and context menu plugin for exteraGram. It adds a bubble-focused message preview, quick reaction controls, and configurable motion and appearance while preserving Telegram's native menu as a compatibility fallback.

## Features

- Bubble-focused message preview with contextual message actions
- Floating quick-reaction bar
- Optional slide-to-select actions, with scrolling on compact screens
- Configurable spring motion and reduced-motion mode
- Frosted backdrop blur on Android 12 and newer, with adjustable intensity
- Adjustable haptic feedback
- Copyable diagnostics for troubleshooting
- Native Telegram menu fallback when the custom menu cannot be opened

## Compatibility

- exteraGram 12.5.1 or newer
- exteraGram SDK 1.4.4.3 or newer

These are the compatibility values declared by the plugin. Device and app builds can still affect individual hooks.

## Add through the exteraGram catalog

[Add this repository to exteraGram](https://t.me/exteraPluginRepo?git=https%3A%2F%2Fgithub.com%2FTenkMunk%2Fios-peek-menu). The repository index is `extera-plugins.json`.

## Install

Download `ios_peek_menu.plugin` from the latest GitHub Release and import it through your exteraGram plugin loader.

## Troubleshooting

If the peek menu does not open, use **Copy diagnostics** in the plugin settings and include the copied report when asking for help. The native Telegram context menu remains available as a fallback when compatibility checks fail.

## Release

See [Releases](../../releases) for versioned downloads and notes.

## Author

[@tenkmunk](https://github.com/tenkmunk)
