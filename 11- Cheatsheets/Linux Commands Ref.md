
A practical reference for commonly used **Linux command-line utilities**, grouped by purpose, showing what each command does and how it’s typically used in everyday terminal work.

---
### `Structure`

##### ==`Informational / System`==

- `whoami` — show current user
- `id` — show user + group IDs
- `uname -a` — show kernel + system info
- `hostname` — show machine hostname
- `date` — show current date/time
- `uptime` — show how long system has been running
- `which <cmd>` — show path of command that will run
- `env` — list environment variables
- `man <cmd>` — open manual page for a command
- `<cmd> --help` — quick usage help for many commands


##### ==`File & Directory Navigation`==

- `ls` — list files
- `ls -la` — list all files (incl hidden) with details
- `mkdir <dir>` — create directory
- `mkdir -p a/b/c` — create nested directories
- `touch <file>` — create empty file / update timestamp
- `cp <src> <dst>` — copy file
- `cp -r <srcDir> <dstDir>` — copy directory recursively
- `mv <src> <dst>` — move/rename
- `rm <file>` — delete file
- `rm -r <dir>` — delete directory recursively ⚠️
- `rm -rf <dir>` — force delete recursively ⚠️⚠️
- `find <path> -name "*.log"` — find files by name pattern
- `locate <name>` — find files via index (if configured)
- `tree` — show directory tree (if installed)


##### ==`Viewing / Printing File Content`==

- `cat <file>` — print file contents
- `less <file>` — view file with paging/search
- `head <file>` — first 10 lines
- `head -n 50 <file>` — first 50 lines
- `tail <file>` — last 10 lines
- `tail -f <file>` — follow appended output (logs)
- `wc <file>` — count lines/words/bytes
- `wc -l <file>` — count lines
- `nl <file>` — print with line numbers
- `grep "text" <file>` — search for text
- `grep -R "text" <dir>` — recursive search
- `sed 's/old/new/g' <file>` — stream text replace
- `awk '{print $1}' <file>` — column-based processing


##### ==`Security / Permissions`==

- `chmod 644 <file>` — set permissions (rw-r--r--)
- `chmod +x <file>` — make executable
- `chmod -R 755 <dir>` — recursively set permissions
- `chown user:group <file>` — change owner + group
- `chown -R user:group <dir>` — recursively change ownership
- `sudo <cmd>` — run command as root (if allowed)
- `sudo -l` — show allowed sudo commands
- `passwd` — change user password (if permitted)


##### ==`Networking`==

- `ip a` — show network interfaces + IPs
- `ip r` — show routing table
- `ping <host>` — test reachability
- `curl <url>` — HTTP request (download/test APIs)
- `curl -I <url>` — fetch headers only
- `wget <url>` — download file (if installed)
- `nslookup <domain>` — DNS lookup
- `dig <domain>` — detailed DNS lookup (if installed)
- `ss -tulpn` — list listening ports/processes
- `netstat -tulpn` — legacy port listing (if installed)
- `traceroute <host>` — route path (if installed)
- `ssh user@host` — remote shell login
- `scp <src> user@host:<dst>` — copy over SSH
- `rsync -av <src> <dst>` — efficient sync/copy


##### ==`Archiving & Compression`==

- `tar -cf archive.tar <dir>` — create tar archive
- `tar -xf archive.tar` — extract tar archive
- `tar -czf archive.tar.gz <dir>` — tar + gzip compress
- `tar -xzf archive.tar.gz` — extract tar.gz
- `tar -cjf archive.tar.bz2 <dir>` — tar + bzip2 compress
- `tar -xjf archive.tar.bz2` — extract tar.bz2
- `tar -cJf archive.tar.xz <dir>` — tar + xz compress
- `tar -xJf archive.tar.xz` — extract tar.xz
- `gzip <file>` — gzip compress (creates `<file>.gz`)
- `gunzip <file>.gz` — gzip decompress
- `zip -r archive.zip <dir>` — create zip
- `unzip archive.zip` — extract zip

---
### `Connected Notes`

- [[Linux Utilities]]