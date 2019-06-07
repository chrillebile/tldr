# nnn

> Interactive terminal file manager and disk usage nalyzer.
> More information: <https://github.com/jarun/nnn>.

- Open file manager at current directory, optional: at given directory from current:

`nnn {{path/to/directory}}`

- Open an existing bookmark:

`nnn -b {{bookmark_name}}`

- Show hidden files:

`nnn -d`

- Start in disk usage analyzer mode:

`nnn -S`

- Start in light mode (fewer details):

`nnn -l`

- Copy selected file path to file_out, or stdout if file_out='-':

`nnn -p {{file_out}}`

- Use substring matching for filters instead of regex:

`nnn -s`

- Use version compare to sort files:

`nnn -n`
