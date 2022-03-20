GRDC(6) - Games Manual

# NAME

**grdc** - grand digital clock (curses)

# SYNOPSIS

**grdc**
\[**-s**]
\[*number*]

# DESCRIPTION

**grdc**
runs a digital clock made of reverse-video blanks on a curses
compatible screen.
With an optional numeric argument
*number*
it stops after
*number*
seconds (defaulting to never).
The optional
**-s**
flag makes digits scroll as they change.
If the terminal is too slow to keep up,
**grdc**
will skip seconds.

# AUTHORS

Amos Shapir,
modified for curses by
John Lupien.

macOS 12.3 - February 6, 2019
