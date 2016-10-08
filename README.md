# Custom Vim Snippets

This is the artchive of custom UltiSnips Vim snippets. Most ported from textmate. 

If you want to add to this, send a pull request.

## Installation

`cd ~.vim/bundle/vim-snippets`

`git clone git@github.com:PuddletownDesign/custom-snippets.git`

## Settings in `.vimrc`

This might change at anytime, I don't know, I'm still figuring it out.

```
let g:UltiSnipsExpandTrigger="<tab>"
let g:UltiSnipsJumpForwardTrigger="<tab>"
let g:UltiSnipsJumpBackwardTrigger="<s-tab>"

let g:UltiSnipsEditSplit="vertical"
let g:UltiSnipsSnippetsDir='~/.vim/bundle/vim-snippets/custom-snippets'
let g:UltiSnipsSnippetDirectories=['custom-snippets']
```

For more info check the offical doc

* https://github.com/SirVer/ultisnips/blob/master/doc/UltiSnips.txt
