# Vim

## Modes
- Normal Mode
- Insert Mode
- Command Mode
- Visual Mode

## Buffers, Tabs and Windows
-   Buffers
    -   List buffers: `:ls`
    -   Next buffer: `bn`
    -   Previous buffer: `bp`
    -   Nth buffer: `b number`
    -   Open a file on the buffer: `b fileName`
-   Windows
    -   
-   Tabs
    -   New tab: `:tabnew <tabname>`
    -   Close tab: `:tabc`
    -   Next tab: `:tabn`
    -   Previous tab: `:tabp`
    -   List tabs: `:tabs`
    -   Switch between tabs: `gt`, `1gt`

## Filetypes
Vim can detect the type of the file that is edited.
-   Load filetype files
    -   Option: `filetype on/off`, `filetype plugin on/off`, `filetype indent on/off`
    -   Location: `$VIMRNTIME/filetype.vim`
    -   Set the filetype manually: `set filetype=idl`
