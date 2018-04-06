# Add Copyright for Vim

vim-copyright is a plug for your file to add/update copyright by bbxytl.

## Installation

Copy the file on your .vim/plug folder.

### Vundle

```
Bundle "nine2/vim-copyright"
```

## Useg

add the config to your .vimrc to set your name / email :

```
let g:file_copyright_name = "your name"
let g:file_copyright_email = "your email"
```

add the config to auto add copyright to your file:

```
let g:file_copyright_auto_filetypes = ['sh', 'plx', 'pl', 'pm', 'py', 'python', 'h', 'hpp', 'c', 'cpp', 'java']
```

- use `:CopyrightAdd` to add copyright for your file.
- use `:CopyrightUpdate` to update copyright.

## Copyright

- python file:

```
# ====================================================
#   Copyright (C)2018 All rights reserved.
#
#   Author        : your name
#   Email         : your email
#   File Name     : eg.py
#   Last Modified : 2018-04-06 14:27
#   Describe      :
#
# ====================================================
```

- cpp file:

```
/* ====================================================
#   Copyright (C)2018 All rights reserved.
#
#   Author        : your name
#   Email         : your email
#   File Name     : eg.cpp
#   Last Modified : 2018-04-06 14:27
#   Describe      :
#
# ====================================================*/
```

