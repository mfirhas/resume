Tex Resume.

### Installing and Running TexLive(Unix)
 - Run sudo apt update
 - Go to https://www.tug.org/texlive/
 - Go to https://www.tug.org/texlive/acquire-netinstall.html
 - Download install-tl-unx.tar.gz
 - Extract and run script in it(install-tl)
 - Enter command: i
 - Add these to .profile:
 > export PATH=/usr/local/texlive/2019/bin/x86_64-linux:$PATH 

 > export MANPATH=/usr/local/texlive/2019/texmf-dist/doc/man 

 > export INFOPATH=/usr/local/texlive/2019/texmf-dist/doc/info
 - Restart
 - Run .tex files with `xelatex filename.tex`


*Template by Byungjin Park in [Awesome-CV](https://github.com/posquit0/Awesome-CV)*