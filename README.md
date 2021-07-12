# tty-stable-shell
linux cheetsheet for tty stable shell on linux

make sure you have taken reverse to bash shell

python -c 'import pty;pty.spawn("/bin/bash")'
or 
python3 -c 'import pty;pty.spawn("/bin/bash")'

export TERM=xterm256

^z 

stty raw -echo

fg

enter
