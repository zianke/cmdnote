# cmdnote

`cmdnote` is a command line tool which stores your future commands. It can help you to save time in your next demo.

![demo](demo.gif)

## Installation

```
pip3 install cmdnote
```

**Important**: Please add the following command to your `.bash_profile`, `.bashrc` or other startup script:

```
eval "$(cmdnote func)"
```

## Usage
```
usage: cmdnote [-h]
               {func,append,insert,list,next,prev,seek,clear,play,config} ...

cmdnote is a command line tool which stores your future commands.

optional arguments:
  -h, --help            show this help message and exit

sub-commands:
  {func,append,insert,list,next,prev,seek,clear,play,config}
                        cmdnote sub-commands
    func                print the cmdnote function for CLI initialization
    append              append commands to the end of note
    insert              insert commands to the beginning of note
    list                list future commands
    next                get the next command to run
    prev                get the previous command to run
    seek                set the note's current position
    clear               clear future commands
    play                run all future commands
    config              configure cmdnote
```