<img src="http://rawgit.com/thesharp/maglev/master/logo/logo.svg">

# Maglev

My variation of [original maglev theme](https://github.com/caiogondim/maglev).

## Screenshot

    TODO: Add screenshot

The annotated screenshot:

    TODO: Add annotated screenshot

## Installing

See [installing tpm plugins](https://github.com/tmux-plugins/tpm#installing-plugins).

You will have to declare the plugins and the theme on your `.tmux.conf`:

```bash
# Start windows and panes at 1, not 0
set -g base-index 1
set -g pane-base-index 1

set-option -g status-position top

set-option -g repeat-time 0

# Removes ESC delay
set -sg escape-time 0

# List of plugins
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'thesharp/maglev'
set -g @plugin 'tmux-plugins/tmux-sensible'
set -g @plugin 'tmux-plugins/tmux-resurrect'
set -g @plugin 'tmux-plugins/tmux-continuum'
set -g @plugin 'tmux-plugins/tmux-prefix-highlight'

# Initialize tmux plugin manager
run '~/.tmux/plugins/tpm/tpm'
```

Some dependencies:
- [tmux](http://tmux.github.io/)
- [tpm](https://github.com/tmux-plugins/tpm)
- [tmux-prefix-highlight](https://github.com/tmux-plugins/tmux-prefix-highlight)
- [Powerline patched font](https://github.com/powerline/fonts): I specifically use [this patched Monaco](https://gist.github.com/rogual/6824790627960fc93077)

## Credits
- Icon created by Katya Sotnikova from The Noun Project
- Original theme by [@caiogondim](https://github.com/caiogondim)
