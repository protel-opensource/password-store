# Simple Password Store

<div style="font-style: typewriter, fixed;">by Jason Donenfeld &lt;Jason@zx2c4.com&gt;</div>

with fixes for more usable listing without the brain-dead tree tool.

This is a very simple password store that encrypts passwords using gpg and
places the encrypted password in a directory. It can generate new passwords
and keep track of old ones.

Visit the project page for more information: http://www.passwordstore.org/

Please see the man page for documentation and examples.

Depends on:
- bash
  http://www.gnu.org/software/bash/
- GnuPG2
  http://www.gnupg.org/
- git
  http://www.git-scm.com/
- xclip
  http://sourceforge.net/projects/xclip/
- tree >= 1.7.0
  http://mama.indstate.edu/users/ice/tree/
- GNU getopt
  http://www.kernel.org/pub/linux/utils/util-linux/
  http://software.frodo.looijaard.name/getopt/
- qrencode
  https://fukuchi.org/works/qrencode/
