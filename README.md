Number of command
===

# Description
This is countting and outputting program about using command.  

# Usage
``` zsh
cat ~/.zshrc_history | awk '{print$1}' | sort | uniq -c | sort -rn | head -3
```
