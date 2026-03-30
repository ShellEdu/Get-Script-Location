# Get-Script-Location
https://www.google.com/search?q=bash+get+script+directory https://stackoverflow.com/questions/59895/how-do-i-get-the-directory-where-a-bash-script-is-located-from-within-the-script # Works: `SCRIPT_DIR=$( cd -- "$( dirname -- "${BASH_SOURCE[0]}" )" &amp;> /dev/null &amp;&amp; pwd )`
