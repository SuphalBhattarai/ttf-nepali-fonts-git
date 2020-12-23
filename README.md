# nepali-fonts
nepali fonts to install from aur package ttf-Nepali-fonts

Arch users can use ttf-nepali-fonts-git package from the aur or use the following commands (base-devel package must be installed )

$ git clone https://gitlab.com/Suphal/ttf-nepali-font-git.git 


$ makepkg -si

Debian or ubuntu users can use following commands to install (Arch users without base-devel package can use following commands ) 


$ git clone https://gitlab.com/Suphal/ttf-nepali-font-git.git


$ sudo cp -r fonts/* /usr/share/fonts/TTF/


$ fc-cache -f


There is also a site-code for converting text from preeti to unicode which can help to put nepali text in applications that only support unicode
To use this tool you can just open the index.html file.
