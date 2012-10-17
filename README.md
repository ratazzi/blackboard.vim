# blackboard.vim

Clone of the Blackboard theme from textmate, work with `xterm-256color`.

## Usage

    if has('gui_running')
        colorscheme ratazzi
    elseif &t_Co > 255 
        " xterm-256color
        colorscheme terminal
    else
        " xterm-color
        colorscheme default
    endif
