# NTop - Console Task Manager
## Usage
### Options

| Option | Meaning |
|:---|:---|
| `-C` | Use monochrome color scheme. |
| `-h` | Display help info. |
| `-p` PID, PID... | Show only the given PIDs. |
| `-n` NamePart, NamePart... | Show only processes containing at least one of the name parts. |
| `-s` COLUMN | Sort by this column. |
| `-u` USERNAME | Only display processes belonging to this user. |
| `-v` | Print version. |

### Interactive commands

| Key(s) | Purpose |
|:---|:---|
| Up and Down Arrows, <kbd>PgUp</kbd> and <kbd>PgDown</kbd>, <kbd>j</kbd> and <kbd>k</kbd> | Scroll the process list. |
| <kbd>CTRL</kbd> + Left and Right Arrows | Change the process sort column. |
| <kbd>g</kbd> | Go to the top of the process list. |
| <kbd>G</kbd> | Go to the bottom of the process list. |
| <kbd>Space</kbd> | Tag a selected process. |
| <kbd>U</kbd> | Untag all tagged processes. |
| <kbd>K</kbd> | Kill all tagged processes. |
| <kbd>I</kbd> | Invert the sort order. |
| <kbd>F</kbd> | Follow process: if the sort order causes the currently selected process to move in the list, make the selection bar follow it. Moving the cursor manually automatically disables this feature. |
| <kbd>n</kbd> | Next in search. |
| <kbd>N</kbd> | Previous in search. |

### Vi commands

| Command(s) | Purpose |
|:---|:---|
| `:exec` CMD | Executes the given Windows command. |
| `:kill` PID(s) | Kill all given processes. |
| `:q`, `:quit` | Quit NTop. |
| `/PATTERN`, `:search` PATTERN | Do a search. |
| `:sort` COLUMN | Sort the process list after the given column. |
| `:tree` | View process tree. |

## Configuration

The color scheme can be customized through the [ntop.conf](ntop.conf) file. Follow link for example.

## Source

- [ksc fork](https://github.com/KarlSchu/NTop/)
- [orig repo](https://github.com/gsass1/NTop/)
