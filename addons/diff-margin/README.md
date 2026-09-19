# Diff margin

Diff Margin is a Godot plugin. Please see official website for [instructions to install](https://docs.godotengine.org/en/stable/tutorials/plugins/editor/installing_plugins.html).

Diff Margin displays Git changes of the currently edited file on Godot script editor margin.

Customization:
- Git binary path (defaults to `git`, or set the full path to `git.exe`)
- Gutter width
- Gutter colors

Tested on Godot 4.3 and 4.7 Windows.

For Godot 4.7, use the current version of this plugin. Older versions call a
removed `EditorSettings` method and stop while activating.

All settings can be changed in the `Editor Settings` under `Plugin` -> `Diff margin`

![Editor](screenshot1.png)
