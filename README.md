# Mizar-Vim-Syntax-Highlight
# Version: 8.1.08_5.50.1318

installation:

```
cd mizar-vim-syntax-highlight
mkdir -p ~/.vim/syntax
cp miz.vim ~/.vim/syntax
```

file type detect:

```
mkdir -p ~/.vim/ftdetect
touch ~/.vim/ftdetect/miz.vim
echo "au BufRead,BufNewFile *.miz set filetype=miz" >> ~/.vim/ftdetect/miz.vim
echo "au BufRead,BufNewFile *.abs set filetype=miz" >> ~/.vim/ftdetect/miz.vim
```

enjoy!
Shawn
