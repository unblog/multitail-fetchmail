# Multitail expression for fetchmail logs

MultiTail is an open source ncurses utility that can be used to display multiple logfiles to standard output in a single window or a single shell that shows last few lines of logfiles in a real-time like tail command which split console into more subwindows (much like screen command). It also supports color highlighting, filtering, adding and deleting windows and much more.

Multitail comes with several predefined color highlighting schemas, such as something for Apache and Postfix logs. Because no schema is provided for fetchmail, I created a schema able for color highlighting fetchmail log, i.e. /var/log/fetchmail

## Usage:

`$ multitail -cS fetchmail /var/log/fetchmail`