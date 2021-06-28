## [Bash scripting cheatsheet](https://devhints.io/bash)

This is a quick reference to getting started with Bash scripting.

## [Shell Style Guide - Google](https://google.github.io/styleguide/shellguide.html)
Which Shell to Use
Bash is the only shell scripting language permitted for executables.

Executables must start with #!/bin/bash and a minimum number of flags. Use set to set shell options so that calling your script as bash script_name does not break its functionality.

Restricting all executable shell scripts to bash gives us a consistent shell language that’s installed on all our machines.

The only exception to this is where you’re forced to by whatever you’re coding for. One example of this is Solaris SVR4 packages which require plain Bourne shell for any scripts.<br>

[A Bash Template(cheat sheet) is very Useful](https://medium.com/codex/a-bash-template-cheat-sheet-is-very-useful-f8207b442e78)

As a PaaS developer, writing shell scripts is inevitable, though I only need to write them very occasionally, once a month maybe. I can’t say it is tough but admit it is not easy. The reasons are
- It takes your effort to adapt to the syntax since it is different from commonly used high-level languages.
- To be proficient in writing, you need to master more built-in variables.
- Debug is always not easy.
- Be cautious about error control. Extra attention is required when it comes to files deletion.

