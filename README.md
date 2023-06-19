# neoneofetch
Clone this repo into your home directory  

Rename it to .neoneofetch  

Ensure that you have neofetch installed  

Then append the following lines to ~/.bashrc  
```
# aliases for neofetch
alias aperturefetch="neofetch --ascii ~/.neoneofetch/aperture.txt --ascii_colors 6 11"
alias catfetch="neofetch --ascii ~/.neoneofetch/cat.txt"
alias dragonfetch="neofetch --ascii ~/.neoneofetch/dragon.txt --ascii_colors 1 7 3"
alias lizardfetch="neofetch --ascii ~/.neoneofetch/lizard.txt"
alias nyarchfetch="neofetch --ascii ~/.neoneofetch/nyarch.txt --gap '-250'"
alias rustfetch="neofetch --ascii ~/.neoneofetch/rust.txt --ascii_colors 1"
alias xeniafetch="neofetch --ascii ~/.neoneofetch/xenia.txt --ascii_colors 9 7 214"

alias neoneofetch="bash ~/.neoneofetch/neoneofetch"
```
