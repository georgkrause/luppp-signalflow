# luppp-signalflow

Some graphs to document the signal-flow of Luppp

# Legend

- red Box = Jack Output Port
- orange Box = Jack Input Port
- Blue Box = Internal Connection
- Oval = Continous Controller
- dashed line = connection can be disabled
- dotted line = controller has inverse effect on another connection

# Build

To build everything to SVG (recommended), use:
`dot -Tsvg *.dot -O`

For more options, see `dot --help`

# Known Problems

- long way to go to be complete

# Contribute

Help is always welcome, please get in touch by creating an issue, join #openav on freenode or send an email (mail@georg-krause.net). Please feel also free to file any PR if you know something to improve. Thanks :)
