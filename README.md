# Slickwit OH-MY-BASH Theme

![Slickwit](/slickwit-dark.png)

Clone the repository:

```bash
git clone https://github.com/slickwit/slickwit-omb-theme.git
```

In order to use this theme you need to put it in the .oh-my-bash directory.

_[Oh My BASH!](https://ohmybash.nntoan.com/)_

_[Oh My BASH! repository](https://github.com/ohmybash/oh-my-bash.git)_

Once `slickwit` theme is in the `.oh-my-bash/themes` directory then you can change your theme in the `.bashrc` file.

```shell
# Path to your oh-my-bash installation.
export OSH='/.oh-my-bash'

OSH_THEME="slickwit" # folder name of the theme
source "$OSH"/oh-my-bash.sh
```

Features:

- [x] Display Date & Time on open.
- [x] Display current Node Version on open.
- [x] Display time + current path + current git branch (if directory have git)
- [x] Display a random emoji
- [x] Stay in the same directory when opening a new tab