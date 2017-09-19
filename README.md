Number of command
===

# Description
This is counting and outputting command about using command.  

# Usage
``` zsh
cat ~/.zsh_history | awk '{print$1}' | sort | uniq -c | sort -rn | head -3
```
