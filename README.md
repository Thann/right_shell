right_shell
===========

Special SSH URI handler for Rightscale instances.


Linux Installation
------------

Append `mimeapps.list` to the one in `~/.local/share/applications/`
and copy `rsh.desktop` to `~/.local/share/applications/`.

Copy `right_shell` to somewhere in your `$PATH` and make sure it's executable.

Test by running `xdg-open rsh://localhost@b9:1d:09:0a:0f:6a:7f:f7:47:c8:c2:d4:5a:2c:01:40` 
but with the proper fingerprint. It should open a new terminal, confirm the fingerprint, and ssh the localhost.
