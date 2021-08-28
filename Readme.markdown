# Lithochromatic Theme for Vim

---

**Note**: this repo is recreated from the version published on the
VimScripts website at
<https://www.vim.org/scripts/script.php?script_id=4406>.  It's pretty
crude right now, but I'll probably update the Readme and maybe the theme
a bit in the future.

---

Lithochromatic is a minimalist light Vim theme


<table>
  <tr>
   <td>
      <img src="screenshots/singlepane.png"
           title="screenshot with single panel"
           alt="Demo screenshot with line numbers and themse source code.  Light theme with purple, green and blue highlights. Line numbers column with khaki bg and black fg, so that it stands out."/>
    </td>
    <td>
      <img src="screenshots/threepanes.png"
           title="screenshot with three panels"
           alt="screenshot with 3 splits: C code, python code, and markdown. The panel with C has the visual mode on, and the highlight has flashy green bg colour."/>
    </td>
  </tr>
</table>


<!-- TODO: add screenshots here -->

## Installation

I've been away from vim for quite a while, so I don't know which package
manager is used widely these days, but using one should be
straightforward.

To install manually:

    $ mkdir -p ~/.vim/colors/
    $ curl https://raw.github.com/cadadr/vim-lithochromatic/default/colors/lithochromatic.vim > ~/.vim/colors/lithochromatic.vim

Then set your colorscheme to lithochromatic:

```vimscript
if &term=~'xterm' || has("gui_running")
    set t_Co=256
    colorscheme lithochromatic
endif
```

Important: This color scheme only supports 256-color terminals and GUI
Vim.
