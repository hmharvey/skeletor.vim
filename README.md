# First things first
This is the _vim-only_ repository of the [Skeletor-Syntax](https://github.com/ramonmcros/skeletor-syntax) by [@ramonmcros](https://github.com/ramonmcros/), a dark theme for [Atom](https://atom.io/themes/skeletor-syntax), [Prism](https://github.com/ramonmcros/skeletor-syntax/tree/master/prism), [Pygments](https://github.com/ramonmcros/skeletor-syntax/tree/master/pygments) and [Zsh](https://github.com/ramonmcros/skeletor-syntax/tree/master/zsh) inspired by Skeletor from He-Man and the Masters of the Universe.

![Skeletor](https://raw.githubusercontent.com/ramonmcros/skeletor-syntax/master/skeletor-250.png)

## Vim
### Installation
If you use vim + [**pathogen**](https://github.com/tpope/vim-pathogen):
```bash
cd ~/.vim/bundle && \
git clone https://github.com/saltcontent/skeletor.vim.git
```

if you use native [**vim 8 pack feature**](https://shapeshed.com/vim-packages/):  
```bash
git clone https://github.com/salttt/skeletor.vim.git ~/.vim/pack/my-plugins/start/skeletor.vim
```

or just move the [skeletor.vim](https://github.com/salttt/skeletor.vim/blob/master/colors/skeletor.vim) file into `~/.vim/colors` and add the following lines into your `.vimrc` file:  
```vim-script
syntax on
colo skeletor
```

### Screenshots
##### HTML:
![HTML](https://i.imgur.com/MbogUir.jpg)
##### CSS:
![CSS](https://i.imgur.com/PxpW5GM.jpg)
##### Sass:
![Sass](https://i.imgur.com/bUynVA8.jpg)
##### Javascript:
![Javascript](https://i.imgur.com/PA5ZOQG.jpg)
##### PHP:
![PHP](https://i.imgur.com/SHrCSY6.jpg)
##### Markdown:
![Markdown](https://i.imgur.com/X6sbenq.jpg)
##### YAML:
![YAML](https://i.imgur.com/Irf01wx.jpg)

##### Several important highlight groups:  
* "Search" (Last search pattern highlighting):  
!["Search"](https://i.imgur.com/o0KENnB.jpg)
* "MoreMsg" (**more-prompt**: -- More --, -- INSERT --, ...), "Question" (**hit-enter** prompt and yes/no questions):  
!["MoreMsg", "Question"](https://i.imgur.com/ERLQvxc.jpg)
* "MatchParen" (The character under the cursor or just before it, if it is a paired bracket, and its match):  
!["MatchParen"](https://i.imgur.com/jtfW190.jpg)
* "StatusLine" (Status line of current window):  
!["StatusLine"](https://i.imgur.com/nv53aBo.jpg)
* "StatusLineNC" (Status lines of not-current windows):  
!["StatusLineNC"](https://i.imgur.com/tI4HHI0.jpg)
* "Folded" (line used for closed folds):  
!["Folded"](https://i.imgur.com/5IGme8D.jpg)
* "Folded" + "FoldColumn=2":  
!["Folded" + "FoldColumn"](https://i.imgur.com/uoj0nqu.jpg)
* "Visual" (Visual mode selection):  
!["Visual"](https://i.imgur.com/BwloMQ6.jpg)
* "WarningMsg":  
!["WarningMsg"](https://i.imgur.com/clSxfeo.jpg)
* "ErrorMsg":  
!["ErrorMsg"](https://i.imgur.com/9viXEpU.jpg)

>check out [gallery](https://imgur.com/a/EJojD) for more! 

## Full Supported Languages

* HTML
* CSS
* Sass (SCSS)
* Javascript
* PHP
* Markdown
* YAML

(more to come soon)

## Color Palette

 **Color-name**   | **Hex**          | **256 (Xterm)**  | **RGB**          | **HSL**       | **Color**    |
------------------|------------------|------------------|------------------|---------------|:------------:|
 White            | #fdf6e3          | 230              | 253 246 227      | 44° 87% 100%  | ![#fdf6e3](https://placehold.it/25/fdf6e3/000000?text=+)
 Light Blue       | #dce7fd          | 189              | 220 231 253      | 220° 89% 93%  | ![#dce7fd](https://placehold.it/25/dce7fd/000000?text=+)
 Yellow           | #f3e4a2          | 229              | 243 228 162      | 49° 77% 79%   | ![#f3e4a2](https://placehold.it/25/f3e4a2/000000?text=+)
 Orange           | #ffb793          | 216              | 255 183 147      | 20° 100% 79%  | ![#ffb793](https://placehold.it/25/ffb793/000000?text=+)
 Red              | #f36a66          | 203              | 243 106 102      | 2° 85% 68%    | ![#f36a66](https://placehold.it/25/f36a66/000000?text=+)
 Orchid           | #ff8adb          | 213              | 255 138 219      | 318° 100% 77% | ![#ff8adb](https://placehold.it/25/ff8adb/000000?text=+)
 Purple           | #bd93f9          | 141              | 189 147 249      | 265° 89% 78%  | ![#bd93f9](https://placehold.it/25/bd93f9/000000?text=+)
 Blue             | #93b4ff          | 75               | 147 180 255      | 222° 100% 79% | ![#93b4ff](https://placehold.it/25/93b4ff/000000?text=+)
 Blue Gray        | #7b94a5          | 103              | 123 148 165      | 204° 19% 56%  | ![#7b94a5](https://placehold.it/25/7b94a5/000000?text=+)
 Green            | #84fba2          | 121              | 132 251 16       | 135° 94% 75%  | ![#84fba2](https://placehold.it/25/84fba2/000000?text=+)
 Very Light Gray  | #c5c8c6          | 251              | 197 200 198      | 140° 3% 78%   | ![#c5c8c6](https://placehold.it/25/c5c8c6/000000?text=+)
 Background       | #2b2836          | 236              | 43 40 54         | 253° 15% 18%  | ![#2b2826](https://placehold.it/25/2b2836/000000?text=+)
 Comments         | #655e7f          | 60               | 101 94 127       | 253° 15% 43%  | ![#655e7f](https://placehold.it/25/655e7f/000000?text=+)
 Cursor           | #423e53          | 239              | 66 62 83         | 251° 14% 28%  | ![#423e53](https://placehold.it/25/423e53/000000?text=+)
 Cursor2          | #383546          | 237              | 56 53 70         | 251° 14% 24%  | ![#383546](https://placehold.it/25/383546/000000?text=+)

## Credit:
* Thanks to [@ramonmcros](https://github.com/ramonmcros/) for making the [Skeletor-Syntax](https://github.com/ramonmcros/skeletor-syntax).
* Theme inspired by [Skeletor](http://en.wikipedia.org/wiki/Skeletor) and [@zenorocha's dracula-theme](https://github.com/zenorocha/dracula-theme).
