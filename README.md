# My Custom Keybindings For VSCode

I got fed up with taking my fingers off the home row to press arrow keys for cursor navigation. Thats what my keybindings are designed to avoid.

I also include some of the default keybindings that are useful. My ones mostly don't overwrite any of these, I think its just the delete line that is overwritten.

## Where to put the file?

It goes here: `~/.config/Code/User/keybindings.json`. I think this file is empty if you haven't added any of your own keybindings, but you might want to check this.

```sh
cp ./keybindings.json ~/.config/Code/User/keybindings.json
```

## My VSCode Custom

Hold Alt for text select

- Ctrl + Shift + h (step L) ; (step R) i (up) k (down)
- Ctrl + Shift + j (step word L) l (step word R)
- Ctrl + Shift + < (Home) > (End)
- Ctrl + Shift + Alt + i (move line up) k (move line down)
- Ctrl + Shift + o (delete line)
- Ctrl + Shift + - (page up) + (page down)

Sidepanel focus

- Ctrl + Shift + i (up) j (down)
- Ctrl + Shift + j (new folder) l (new file)
- Ctrl + Shift + o (delete file) ; (edit file)

## VSCode default:

**These are useful default keybindings to know**

Cursor navigation/text editor:

- Ctrl + Shift + Enter: insert line
- Ctrl + Shift + K: delete line (my custom used O not K)
- Alt + Up/Down: move current line up/down
- Ctrl + Shift + Up/Down: add cursors on multiple lines (Esc will cancel)
- Ctrl + G: navigate to line number
- Ctrl + K Ctrl + 0: Fold All code blocks/markdown sections
- Ctrl + K Ctrl + J: Unfold All
- F2: rename highlighted file

Search & Replace

- Enter: replace current selection
- Ctrl + Alt + Enter: relace all
- Alt + Enter: edit found selection in editor panel
- Ctrl + Shift + h: replace in file
- Shift + Tab: back tab to get to replace toggle (so mouse doesn't need to be used)

Toggle panels:

- Ctrl + J: toggle between terminal and code panel
- Ctrl + j: toggle terminal visibility. Ctrl + `: toggle focus
- Ctrl + b: toggle file explorer visibility
- Ctrl + 0: toggle file explorer focus
- Ctrl + Tab: cycle tabs
- Alt + number: toggle to tab
- Ctrl + groupNumber: toggle to tab group
