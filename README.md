# Dotfiles

Ovde se nalaze konfiguracije za alate koje koristim.
# Tutorijali koji su mu pomogli:
- Instalacija Arch/Hyprland: https://www.youtube.com/watch?v=lfUWwZqzHmA&t=1307s
- Tmux instalacija i konfiguracija: https://www.youtube.com/watch?v=DzNmUNvnB04&t=418s
- Neovim konfiguracija: https://www.youtube.com/watch?v=6pAG3BHurdM
# Trenutno sta koristim
- Arch linux
- Hyprland
- Waybar
- Wofi
- neovim
- tmux
- kitty

# Nvim commands
#### MOVE BETWEEN WINDOWS
- ctrl+h
- ctrl+j
- ctrl+k
- ctrl+l

#### KEYMAPS
- j+k - Exit insert mode
- space+n+h - Clear search highlights
- space+s+v - Split window vertically
- space+s+h - Split window horizontally
- space+s+e - Make splits equal size
- space+s+x - Close curent split

#### WHEN THE CODE IS HIGHLIGHTED WE CAN MOVE IT UP AND DOWN WITH: 
- J
- K

#### WHEN WE SEARCH, WE CAN GO TROUGH THE RESULTS UP AND DOWN WITH:
- n
- N

#### HALF PAGE JUMPING:
- ctrl+d
- ctrl+u

#### AUTO SESSION
- space+w+s - Save session for auto session root dir
- space+w+r - Restore session for cwd

#### COMMENTS
- g+c+c - comment/uncomment line where the cursor is placed 
- g+c - highlighted code gets commented/uncommented

#### FORMATING
- space+m+p - formating the whole file (.stylua.toml - options for formating)

#### HARPOON
- space+a - Mark file with harpoon
- ctrl+e - Toggle harpoon quick menu
- ctrl+v - Go to the first harpoone mark
- ctrl+b - Go to the second harpoone mark
- ctrl+n - Go to the third harpoone mark
- ctrl+m - Go to the fourth harpoone mark

#### MAXIMIZER
- space+s+m - Maximize/minimize a split

#### NVIM-TREE
- space+e+e - Toggle file explorer
- space+e+f - Toggle file explorer on current file
- space+e+c - Collapse file explorer
- space+e+r - Refresh file explorer

#### TELESCOPE
- ctrl+k - Move to prev result
- ctrl+j - Move to next result
- ctrl+q - Close suggestions
- space+f+f - Fuzzy find files in cwd
- space+f+r - Fuzzy find recent files
- space+f+s - Find string in cwd
- space+f+c - Find string uder cursor in cwd

#### TREESITER
- ctrl+space - Select word under cursor
- ctrl+space+space - After second time it selects whole line
- ctrl+space+space+space - After third time it selects whole block and so one

#### TROUBLE
- space+xw - Open trouble workspace diagnostics
- space+xd - Open trouble document diagnostics on error where is our cursor
- space+xq - Open trouble quickfix list
- space+xl - Open trouble location list

#### UNDOTREE
- space+u - Toggle undotree

#### VIMWIKI
- space+w+w - Open vimwiki

# Hyprland commands
- alt+enter - Open terminal
- alt+q - Close the active window
- alt+shift+l - Lock the screen
- alt+m - Show the logout window
- alt+shift+m - Exit hyprland all together
- alt+n - Show the file browser
- alt+v - Allow windows to float
- alt+d - Search
- alt+w - Open firefox
- alt+p - Decreases window size to middle
- alt+shift+j - Toggles active window to horizontal/vertical position
- alt+s - Take a screenshot
- alt+f - Maximizez active window
- alt+shift+f - Full screen active window

#### Moving between windows(including between screens):
- alt+h
- alt+j
- alt+k
- alt+l

#### Moving between workspaces:
- alt+1
- alt+2
- alt+3
- alt+4
- alt+5
- alt+6
- alt+7
- alt+8
- alt+9
- alt+10

#### Move active window to the workspace:
- alt+shift+1
- alt+shift+2
- alt+shift+3
- alt+shift+4
- alt+shift+5
- alt+shift+6
- alt+shift+7
- alt+shift+8
- alt+shift+9
- alt+shift+10

- alt+left_click - Move active window with the mouse
- alt+scrolle_wheel - Move active window between workspaces

# Tmux commands
#### We have windows which consist of pains inside does windows

- ctrl+s - prefix key
- prefix+c - creating new window
- prefix+windowNumber - choosing active window
- prefix+n / prefix+p - cycle between windows
- prefix+& - kill current active window
- prefix+% - split a window horizontaly with pains
- prefix+" - split a window verticaly with pains
- prefix+} / prefix+{ - swpping pains left and write
- prefix+z - toggle full screen mode
- prefix+x - closing pain

#### Navigation through pains:
- ctrl+h
- ctrl+j
- ctrl+k
- ctrl+l

