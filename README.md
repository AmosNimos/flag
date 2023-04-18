<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <body>
    <h1>Flag - A Bash script for parsing command line flags</h1>
    <p>Flag is a Bash script that makes it easy to parse command line flags in your Bash scripts. It uses the `getopts` Bash built-in command to parse flags and convert them to easy-to-use variables in your script.</p>

    <h2>Usage</h2>
    <p>To use `flag` in your Bash scripts, first source the script:</p>
    <pre><code>source /path/to/flag.sh</code></pre>
    <p>Then, call the `flag` function and pass a string of valid flag options, like this:</p>
    <pre><code>flag "$@"</code></pre>
    <p>The function takes one argument which is a string of valid flag options. Lowercase flag represent flag that don't take a value and uppercase flag represent flag that take a value. The variables set will be `flag_[flag]`, for example `flag_a` for flag `-a`.</p>

    <h2>License</h2>
    <p>Flag is licensed under the MIT License. See the LICENSE file for details.</p>

    <h2>Author</h2>
    <p>Flag was created by Amosnimos.</p>
  </body>
</html>
