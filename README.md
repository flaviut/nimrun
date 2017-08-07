# nimrun

A wrapper around the Nim compiler to allow for easy scripting of Nim. Puts
all temporary files in a temporary directory and cleans up after itself.

This script is implemented in shell. If you'd like a pure Nim implementation,
[check out Jeff Ciesielski's nimr][jeff-nimr], which can be installed by just
running `nimble install nimr`!

[jeff-nimr]: https://github.com/Jeff-Ciesielski/nimr

# Usage
1. Download the script from [here][nimrun] and add it to your path.
2. Use it in one of the following ways:
   - add `#!/usr/bin/env nimrun` at the beginning of your script
   - execute the nim file with it, for example, `nimrun file.nim args`

[nimrun]: https://raw.githubusercontent.com/flaviut/nimrun/master/nimrun


# Possible future extentions:
 - cache compilation results for a while
 - configurable temporary directory
 - allow for custom `nim c` parameters
