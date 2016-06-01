# vim-fortress
FORTRESS frontend for vim

We are assuming, you installed https://github.com/rscircus/fortress already.

By default this calls the style.ini in the local dir from which vim was started in.

Add the following to your `.vimrc`
```
map <leader>ff :call fortress#format()<cr>
imap <leader>ff :call fortress#format()<cr>
```
