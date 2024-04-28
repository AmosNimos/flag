# Flag - A Bash script for parsing command line flags

🏴‍☠️ Description
-------
Flag is a Bash script that simplifies the process of parsing command-line flags in your Bash scripts. It parse flags and convert them to easy-to-use variables in your script.

🏴‍☠️ What does it stand for?
-------
Flag stands for "Friendly Linux Argument Gatherer" or, if you like recursion, "Flag: Linux Argument Gatherer."

🏴‍☠️ Usage
-------
To use `flag` in your Bash scripts, simply source the script and pass the arguments directly to it, like this:

```bash
source /path/to/flag.sh "$@"
```
The script parses both short flags (single-letter flags preceded by a single dash, e.g., `-a`) and long flags (multi-character flags preceded by two dashes, e.g., `--test`). Flags without a value are set to 1 (true as boolean). The variables set will be `flag_[flag]`, for example, `flag_a` for flag `-a` and `flag_test` for `--test`.

🏴‍☠️ License
-------
Flag is licensed under GNU GPL. See the LICENSE file for details.

🏴‍☠️ Author
-------
Flag was created by Amosnimos.

[GitHub](https://github.com/AmosNimos)
