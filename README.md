# Linux-settings

Add .bash_profile to syntax:
  
  In: /usr/share/vim/vim74/filetype.vim

au BufNewFile,BufRead .bashrc*,bashrc,bash.bashrc,.bash[_-]profile*,.bash[_-]logout*,.bash[_-]aliases*,*.bash,*/{,.}bash[_-]comple     tion{,.d,.sh}{,/*},*.ebuild,*.eclass call SetFileTypeSH("bash")
