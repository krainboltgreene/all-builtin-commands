# all-builtin-commands README

Visual Studio Code's team refused to add command palettes to a lot of commands built into the editor. Some don't even have keybindings (???) or descriptions (????????). This can make things more complicated for users than needs to be. The command palette's job is to provide contextual human interfaces for the actions an editor can do on behalf of the user. For example the command `cursorWordStartRight` which doesn't have a keymap OR a description, can be given a title via the command palette of `"Move cursor to start of next word"` with this extension.

This is a powerful addition because new users don't have to learn keybindings right off the bat. A perfect example of this is in my Github issue where I describe this problem. A random user told me I could solve this by simply typing CTRL+S -> CTRL+K to see all the key mappings. Hilariously is not the keybinding on macs! But you know what's universal? Typing "shortcuts" into command palette.

I've added a lot of cursor and select commands that were missing from atom, but I would love more! Please submit!

### 1.0.0

Initial release of all-builtin-commands.
