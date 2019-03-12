# My ST Terminal Configuration

# Features

My additions:

+ Using the `Fura Code Mono Nerd` Powerline font to line up with my favoured set-up with `Vim` (using [SpaceVim](https://spacevim.org));
+ Careful font sizing to enable "gap free" alignment on a HiDPI screen (Dell XPS 15 9550 4K);
+ Setting of terminal type as `xterm-256color` to ensure the right passthrough of vars from `tmux` to `vim` (nvim), such as cursor shape;
+ Set shell to `zsh`.

## Changes from the original Fork

Luke's original fork brings the following:

The [suckless terminal (st)](https://st.suckless.org/) with some additional features:

+ Compatibility with `Xresources` and `pywal` for dynamic colors.
+ Default [gruvbox](https://github.com/morhetz/gruvbox) colors otherwise.
+ Transparency/alpha, which is also adjustable from `~/.Xresources`.
+ Default font is system "mono" at 16pt, meaning the font will match your system font.
+ Very useful keybinds including:
	+ Copy is alt-c, paste is alt-v or alt-p pastes from primary selection
	+ Alt-l feeds all urls on screen to dmenu, so they user can choose and
	  follow one (requires xurls and dmenu installed).
	+ Zoom in/out or increase font size with Alt+Shift+k/j or u/d for larger intervals.
	+ Hold alt and press either ↑/↓ or the vim keys k/j to move up/down in the terminal.
	+ Shift+Mouse wheel do the same.
	+ Alt-u and Alt-d scroll back/forward in history a page at a time.
	+ Alt-PageUp and Alt-PageDown will do the same.
+ Vertcenter
+ Scrollback
+ updated to latest version 0.8.1

The following additional bindings were added before I forked this:

+ Scroll through history -- Shift+PageUp/PageDown or Shift+Mouse wheel
+ Increase/decrease font size -- Shift+Alt+PageUp/PageDown
+ Return to default font size -- Alt+Home
+ Paste -- Shift+Insert

## Original Fork

[Luke Smith's](https://github.com/LukeSmithxyz/st)
