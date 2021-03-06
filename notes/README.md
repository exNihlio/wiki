## Unifying my development set up

I've been using VS Code for about two years now. But ultimately I've
decided to switch back to Vim + tmux. To that end, I want to unify my
experience across systems, as I use Ubuntu on my desktop and a Macbook.

My dotfiles, i.e. `.vimrc`, `.bash*`, `.tmux.conf` are all managed in git
and installed with a shell script. But I want to go further. I want a script
that will install system fonts, set up my vim plugins and configure my terminal
so that anytime I get a new system, I can just run `bash install.sh` and be
(mostly) good to go.

First I'm creating a `packages.json` file. This will contain any vim plugins,
system fonts, and other system packages to install. Next we need to install `jq`
to read this in. Which means `install.sh` needs to be able to work for Mac and Linux.

Next we'll create and install our directories `~/.tmux/pack` directory. And clone down
our packages. At writing time, we're just adding `gruvbox` but there will be a few more
plugins to add as well. We also want this to be minimal. We're not rebuilding EMACS into
Vim.

While I've enjoyed using iTerm, I'm looking into replacing it with Kitty. This is for several
reasons:

1. Kitty is multiplatform.

2. Kitty uses a single config file, which makes syncing with Git awesome.

3. Kitty has built in support for displaying images and that is AWESOME.

I am also investigating Alacritty, because I don't really care about splitting windows
or fancy terminal stuff. Tmux will handle that for me.


## VIM Stuff

#### Tab Operations

`gt` == Next Tab
`gT` == Prior Tab
`${tabNumber} gt` == Tab number
`:tabnew` == Open new tab

#### Window Operations
`Ctrl-w <up>|<down>|<left>|<right>`

#### Opening/Closing files
`bd` == Close Buffer/Close file
