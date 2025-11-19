# sudo options and examples

This file lists common `sudo` options, meanings and examples.

## Short options
- `sudo -h` or `sudo --help`  
  Show help text and exit.  
  Example: `sudo --help`

- `sudo -V`  
  Show sudo version information.  
  Example: `sudo -V`

- `sudo -v`  
  Validate/refresh your cached credentials (extend the timeout).  
  Example: `sudo -v`

- `sudo -k`  
  Invalidate the user's timestamp (next sudo will ask for password).  
  Example: `sudo -k`

- `sudo -K`  
  Remove the user's cached credentials completely.  
  Example: `sudo -K`

- `sudo -n`  
  Non-interactive: fail instead of prompting for a password.  
  Example: `sudo -n apt update` (will fail if password required)

- `sudo -u <user>`  
  Run the command as specified user (default is root).  
  Example: `sudo -u www-data systemctl restart nginx`

- `sudo -s`  
  Run a shell as root (preserving environment).  
  Example: `sudo -s`

- `sudo -i`  
  Run login shell as target user (initializes login environment).  
  Example: `sudo -i`

- `sudo -H`  
  Set HOME to the target user's home directory.  
  Example: `sudo -H -u someuser bash -c 'echo $HOME'`

- `sudo -l`  
  List the commands the invoking user is allowed to run (and which require password).  
  Example: `sudo -l`

- `sudo --`  
  End of `sudo` options; following args are the command.  
  Example: `sudo -- ls --color=auto`

## Useful combinations / tips
- Run a single command as another user:
  `sudo -u username command`

- Get a root interactive shell:
  `sudo -i` or `sudo -s`

- Run without password (if you have NOPASSWD in sudoers): `sudo -n command`

## Where to get more details
- `man sudo` — full manual
- `/etc/sudoers` and files under `/etc/sudoers.d/` — configuration for privileges

