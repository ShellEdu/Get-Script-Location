# Get-Script-Location
sch:
https://www.google.com/search?q=bash+get+script+directory
https://www.google.com/search?q=bash+get+script+location

# Answer:
https://stackoverflow.com/questions/59895/how-do-i-get-the-directory-where-a-bash-script-is-located-from-within-the-script
https://askubuntu.com/questions/893911/when-writing-a-bash-script-how-do-i-get-the-absolute-path-of-the-location-of-th

# Works:
```
realpath "$0"
dirname "$(realpath $0)"
```

# Try: `SCRIPT_DIR=$( cd -- "$( dirname -- "${BASH_SOURCE[0]}" )" &amp;> /dev/null &amp;&amp; pwd )`
