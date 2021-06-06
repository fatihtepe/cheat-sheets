Tmux is a terminal multiplexer. Wait, what? Why I need that?
You just connected to a Linux box through SSH, but hey, I want to run more than one command at a time! One shell is just not enough! Use tmux and you can have any number of terminals you want!
You connected to a Linux box through SSH, but hey, I want to run this command forever! Use tmux and you can run any command you want, detach from the terminal and it will keep running. For-eh-vah!
You love the good and old terminal, but you want more power to switch between shells really freaking fast. Use tmux!
You love both the terminal and Vim. Use tmux!

At Ubuntu:
- sudo apt install tmux
At Mac:
- brew install tmux

Download this minimal config file I created at your home sweet home. It has the minimal required to improve your UX on tmux:
- wget https://gist.githubusercontent.com/automata/2a3e8a276b2fd05ae13d086422dc4140/raw/b09631ed5255d32a93cd2e1f396ef52631409fcd/tmux.conf -O ~/.tmux.conf


C-b c                     Create a new window
C-b |                     Split window vertically
C-b -                     Split window horizontally
C-b <arrow keys>          Move between panes
C-b <h,j,k,l>             Move between panes Vim-style
C-b <number>              Go to window number n (listed at bottom)
C-b [                     Enter in "scroll mode".
                          - Use arrows and page-down/up to move
                          - Type Enter to exit the mode.
C-b d                     Detach from session (to get back: tmux a)
  
source: https://aut0mata.medium.com/quick-survival-guide-to-tmux-166b8a4de6a8
