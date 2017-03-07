# syntastic-local-eslint.vim

Prefer local repo install of eslint over global install with syntastic

Installation Instructions
-------------------------

Vundles:

```
Plugin 'inlineblock/syntastic-local-eslint.vim'
```

Whats been added?
-----------------

```
let g:SLESlintChDirMode = (0 | 1)
```
0 = Dont change working directory on file open
1 = Change working directory on file open

