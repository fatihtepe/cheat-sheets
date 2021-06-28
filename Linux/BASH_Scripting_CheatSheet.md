## [Bash scripting cheatsheet](https://devhints.io/bash)

This is a quick reference to getting started with Bash scripting.

## [Shell Style Guide - Google](https://google.github.io/styleguide/shellguide.html)
Which Shell to Use
Bash is the only shell scripting language permitted for executables.

Executables must start with #!/bin/bash and a minimum number of flags. Use set to set shell options so that calling your script as bash script_name does not break its functionality.

Restricting all executable shell scripts to bash gives us a consistent shell language that’s installed on all our machines.

The only exception to this is where you’re forced to by whatever you’re coding for. One example of this is Solaris SVR4 packages which require plain Bourne shell for any scripts.