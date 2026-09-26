this is specifically made for JetBrainsMono font size 11 it may not look properly with other fonts and sizes 

also u have to use kitty for this (i think i may be wrong)

usage

first u have to run kitten icat --z-index=-1 --place 66x14@0x0 --transfer-mode=file ~/jonaszfetch/fetchimage.png  (for size 11 JetBrainsMono)
the image should pop out 
next u have to run fastfetch --logo none | sed 's/^/                              /'  the 's/^/                              /' is the spacing u can adjust it however u want 

thats all but i recommend aliasing it my for example mine r f for the kitten icat command and ff is for fastfetch

alias f='kitten icat --z-index=-1 --place 66x14@0x0 --transfer-mode=file ~/Pictures/fetchimage.png'
alias ff='fastfetch --logo none --pipe false | sed "s/^/                              /"'

any questions or suggestions u can add me on discord: tiktakjas  
