# vim-mmr-snippets
Quick snippets for making a new React component using hooks.

# Installation

* Have vim and Ultisnips installed
* (.vimrc) Add this package

```
Plug 'mreishus/vim-mmr-snippets'
```

* (.vimrc) Add automatic loading via filetypes

```
autocmd FileType javascript UltiSnipsAddFiletypes javascript-react-hook
autocmd FileType typescript UltiSnipsAddFiletypes typescript-react-hook
autocmd FileType typescript.tsx UltiSnipsAddFiletypes typescript-react-hook
```

* Enjoy!

Use these definitions in React: `rhc` and `rhcr` for a new *React Hook Component*.  The version with r at the end adds some redux imports.

In Typescript, use `thc` and `thcr` for a new React Hook Component.  These are
mostly the same as the react versions above, but they add an empty Props
interface.
