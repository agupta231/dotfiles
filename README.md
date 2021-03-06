# dotfiles
My configs for my daily workflow. Included are 
* aliases
* vimrc
* tmux config
* docker shortcuts
* emacs config
* etc

## To install
Simply run `sh repo_to_local.sh` and let the magic happen! However, know that
this **will overwrite** your current config, so make a backup!


## Ultisnip Snipets Documentation
### LaTeX
#### ;b;
Will wrap the inputted text in `\textbf`

#### ;i;
Will wrap the inputted text in `\textit`

#### ;em;
Will wrap the inputted text in `\emph`

#### ;u;
Will wrap the inputted text in `\underline`

#### ;con;
Will create 
``` 
\begin{*inputted text*}
\end{*inputted text*}
```

#### ;gentbl{a}x{b};
Will generate a table of width a and height b

#### ;tr{a};
Will create a row of dimension a

#### ;frac;
Will create a fraction. Outputs `\frac{}{}` 

#### ;ul;
Will create a bulleted list

#### ;des;
Will create a descriptive list

#### ;ol;
Will create an ordered list (enumeration)

#### ;li;
Will create a list item

#### ;nli;
Will create a named list item (`item[] ...`)

## TODO::
* Create a pacman package list so that I can setup a new computer with one
command
* Create a packer package list so that I can setup a new computer with one
command
* Create an `install_all_packages.sh`
