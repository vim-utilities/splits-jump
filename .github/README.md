# Splits Jump
[heading__top]:
  #splits-jump
  "&#x2B06; Vim plugin for jumping between splits swiftly"


Vim plugin for jumping between splits swiftly


## [![Byte size of Splits Jump][badge__main__splits_jump__source_code]][splits_jump__main__source_code] [![Open Issues][badge__issues__splits_jump]][issues__splits_jump] [![Open Pull Requests][badge__pull_requests__splits_jump]][pull_requests__splits_jump] [![Latest commits][badge__commits__splits_jump__main]][commits__splits_jump__main] 



---


- [:arrow_up: Top of Document][heading__top]

- [:building_construction: Requirements][heading__requirements]

- [:zap: Quick Start][heading__quick_start]

- [&#x1F9F0; Usage][heading__usage]

- [&#x1F5D2; Notes][heading__notes]

- [:chart_with_upwards_trend: Contributing][heading__contributing]

  - [:trident: Forking][heading__forking]
  - [:currency_exchange: Sponsor][heading__sponsor]

- [:card_index: Attribution][heading__attribution]

- [:balance_scale: Licensing][heading__license]


---



## Requirements
[heading__requirements]:
  #requirements
  "&#x1F3D7; Prerequisites and/or dependencies that this project needs to function properly"


This repository requires the [Vim][vim__home] text editor to be installed the source code is available on [GitHub -- `vim/vim`][vim__github], and most GNU Linux package managers are able to install Vim directly, eg...


- Arch based Operating Systems


```Bash
sudo packman -Syy

sudo packman -S gawk make vim
```


- Debian derived Distributions


```Bash
sudo apt-get update

sudo apt-get install gawk make vim
```


> Note `gawk` and `make` are only required if **not** utilizing a Vim plugin manager.


______


## Quick Start
[heading__quick_start]:
  #quick-start
  "&#9889; Perhaps as easy as one, 2.0,..."


Clone this project...


```Bash
mkdir -vp ~/git/hub/vim-utilities

cd ~/git/hub/vim-utilities

git clone git@github.com:vim-utilities/splits-jump.git
```


---


If **not** using a plugin manager, then this plugin may be installed via `make install` command...


```Bash
cd ~/git/hub/vim-utilities/splits-jump

make install
```


---


To update in the future use `make upgrade` command...


```Bash
cd ~/git/hub/vim-utilities/splits-jump

make upgrade
```


---


After installation, plugin documentation may be accessed via Vim's `:help` command, eg...


```Vim
:help splits-jump
```


______


## Usage
[heading__usage]:
  #usage
  "&#x1F9F0; How to utilize this repository"


All split actions are relative to current/active split, and intended to be used within Normal mode...


- <kbd>Ctrl</kbd><kbd>h</kbd> Jump towards left split

- <kbd>Ctrl</kbd><kbd>j</kbd> Jump towards lower split

- <kbd>Ctrl</kbd><kbd>k</kbd> Jump towards upper split

- <kbd>Ctrl</kbd><kbd>l</kbd> Jump towards right split


______


## Notes
[heading__notes]:
  #notes
  "&#x1F5D2; Additional things to keep in mind when developing"


This repository may not be feature complete and/or fully functional, Pull Requests that add features or fix bugs are certainly welcomed.


______


## Contributing
[heading__contributing]:
  #contributing
  "&#x1F4C8; Options for contributing to splits-jump and vim-utilities"


Options for contributing to splits-jump and vim-utilities


---


### Forking
[heading__forking]:
  #forking
  "&#x1F531; Tips for forking splits-jump"


Start making a [Fork][splits_jump__fork_it] of this repository to an account that you have write permissions for.


- Add remote for fork URL. The URL syntax is _`git@github.com:<NAME>/<REPO>.git`_...


```Bash
cd ~/git/hub/vim-utilities/splits-jump

git remote add fork git@github.com:<NAME>/splits-jump.git
```


- Commit your changes and push to your fork, eg. to fix an issue...


```Bash
cd ~/git/hub/vim-utilities/splits-jump


git commit -F- <<'EOF'
:bug: Fixes #42 Issue


**Edits**


- `<SCRIPT-NAME>` script, fixes some bug reported in issue
EOF


git push fork main
```


> Note, the `-u` option may be used to set `fork` as the default remote, eg. _`git push -u fork main`_ however, this will also default the `fork` remote for pulling from too! Meaning that pulling updates from `origin` must be done explicitly, eg. _`git pull origin main`_


- Then on GitHub submit a Pull Request through the Web-UI, the URL syntax is _`https://github.com/<NAME>/<REPO>/pull/new/<BRANCH>`_


> Note; to decrease the chances of your Pull Request needing modifications before being accepted, please check the [dot-github](https://github.com/vim-utilities/.github) repository for detailed contributing guidelines.


---


### Sponsor
  [heading__sponsor]:
  #sponsor
  "&#x1F4B1; Methods for financially supporting vim-utilities that maintains splits-jump"


Thanks for even considering it!


With <sub>[![sponsor__shields_io__liberapay]][sponsor__link__liberapay]</sub> you may sponsor vim-utilities on a repeating basis.


Regardless of if you're able to financially support projects such as splits-jump that vim-utilities maintains, please consider sharing projects that are useful with others, because one of the goals of maintaining Open Source repositories is to provide value to the community.


______


## Attribution
[heading__attribution]:
  #attribution
  "&#x1F4C7; Resources that where helpful in building this project so far."


- [GitHub -- `github-utilities/make-readme`](https://github.com/github-utilities/make-readme)

- [StackOverflow -- How to get current relative directory of your Makefile](https://stackoverflow.com/questions/18136918/)

- [StackOverflow -- How to remove the last trailing backslash in GNU Makefile](https://stackoverflow.com/questions/33126425/)

- [StackOverflow -- Makefile execute another target](https://stackoverflow.com/questions/3267145/)

- [YouTube --  nixcasts -- A look through my vimrc](https://www.youtube.com/watch?v=Ad9BhAiAg7o)


______


## License
[heading__license]:
  #license
  "&#x2696; Legal side of Open Source"


```
Vim plugin for jumping between splits swiftly
Copyright (C) 2020 S0AndS0

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```


For further details review full length version of [AGPL-3.0][branch__current__license] License.



[branch__current__license]:
  /LICENSE
  "&#x2696; Full length version of AGPL-3.0 License"


[badge__commits__splits_jump__main]:
  https://img.shields.io/github/last-commit/vim-utilities/splits-jump/main.svg

[commits__splits_jump__main]:
  https://github.com/vim-utilities/splits-jump/commits/main
  "&#x1F4DD; History of changes on this branch"


[splits_jump__community]:
  https://github.com/vim-utilities/splits-jump/community
  "&#x1F331; Dedicated to functioning code"


[issues__splits_jump]:
  https://github.com/vim-utilities/splits-jump/issues
  "&#x2622; Search for and _bump_ existing issues or open new issues for project maintainer to address."

[splits_jump__fork_it]:
  https://github.com/vim-utilities/splits-jump/
  "&#x1F531; Fork it!"

[pull_requests__splits_jump]:
  https://github.com/vim-utilities/splits-jump/pulls
  "&#x1F3D7; Pull Request friendly, though please check the Community guidelines"

[splits_jump__main__source_code]:
  https://github.com/vim-utilities/splits-jump/
  "&#x2328; Project source!"

[badge__issues__splits_jump]:
  https://img.shields.io/github/issues/vim-utilities/splits-jump.svg

[badge__pull_requests__splits_jump]:
  https://img.shields.io/github/issues-pr/vim-utilities/splits-jump.svg

[badge__main__splits_jump__source_code]:
  https://img.shields.io/github/repo-size/vim-utilities/splits-jump


[vim__home]:
  https://www.vim.org
  "Home page for the Vim text editor"

[vim__github]:
  https://github.com/vim/vim
  "Source code for Vim on GitHub"


[sponsor__shields_io__liberapay]:
  https://img.shields.io/static/v1?logo=liberapay&label=Sponsor&message=vim-utilities

[sponsor__link__liberapay]:
  https://liberapay.com/vim-utilities
  "&#x1F4B1; Sponsor developments and projects that vim-utilities maintains via Liberapay"

