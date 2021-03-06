---
date: 2015-12-16T09:24:56-07:00
title: "hugo gen autocomplete"
slug: hugo_gen_autocomplete
url: /commands/hugo_gen_autocomplete/
---
## hugo gen autocomplete

Generate shell autocompletion script for Hugo

### Synopsis


Generates a shell autocompletion script for Hugo.

NOTE: The current version supports Bash only.
      This should work for *nix systems with Bash installed.

By default, the file is written directly to /etc/bash_completion.d
for convenience, and the command may need superuser rights, e.g.:

	$ sudo hugo genautocomplete

Add `--completionfile=/path/to/file` flag to set alternative
file-path and name.

Logout and in again to reload the completion scripts,
or just source them in directly:

	$ . /etc/bash_completion

```
hugo gen autocomplete
```

### Options

```
      --completionfile="/etc/bash_completion.d/hugo.sh": Autocompletion file
      --type="bash": Autocompletion type (currently only bash supported)
```

### Options inherited from parent commands

```
      --log[=false]: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
  -v, --verbose[=false]: verbose output
      --verboseLog[=false]: verbose logging
```

### SEE ALSO
* [hugo gen](/commands/hugo_gen/)	 - A collection of several useful generators.

###### Auto generated by spf13/cobra on 16-Dec-2015
