# Multitail expression for fetchmail logs

MultiTail is an open source ncurses utility that can be used to display multiple logfiles to standard output in a single window or a single shell that shows last few lines of logfiles in a real-time like tail command which split console into more subwindows (much like screen command). It also supports color highlighting, filtering, adding and deleting windows and much more.

## Preface

Multitail comes with several predefined color highlighting schemas, such as for Apache and Postfix and many more daemons. Because no schema is provided for fetchmail, I created a schema able for colorized fetchmail log, i.e. /var/log/fetchmail

## Purpose

Add the lines to your multitail.conf at the end.

## Usage:

`$ multitail -cS fetchmail /var/log/fetchmail`