- Prepend to PATH: PATH="/path/to/file:$PATH"
- Append to PATH: PATH="$PATH:/path/to/file"
- Preventing duplicates in PATH: typeset -U PATH


- Extras:
	Command to spit out path in a nice way:

	$ ==echo $PATH | sed 's/:/\n/g' | sort | uniq -c==

	from: https://medium.com/mkdir-awesome/my-path-variable-is-a-mess-e52f22bfa520



