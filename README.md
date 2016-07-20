# fenix

_respawn a process unless the user really wants to quit_

## manual installation

    sudo install -t /usr/bin fenix

## installation on archlinux

    git clone http://aur.archlinux.org/fenix
    cd fenix
    makepkg -irs

## legal junk

This project is copyright © Edward Hernández <ehernandez@email.wm.edu> and
released under the terms of the GNU General Public License version 3, available
at <https://www.gnu.org/licenses/gpl.txt>.

This project is a derivative work of a project called 'phoenix', which is
copyright © martin f. krafft <madduck@madduck.net> and also released under the
terms of the Artistic Licence 2.0. I have jumped through the following hoops in
order to comply with this license:

  - There is a copy of the original source of 'phoenix' in the file 'ORIGINAL'.
    If you want to run the original 'phoenix' instead of my updates, you can do
    so by running `sudo install ORIGINAL /usr/bin/phoenix`

  - I am required to tell you that you can run `diff fenix ORIGINAL` to see
    what changes I have made to the original. In short, I have added the
    `--timeout` option.

  - The name has been changed from 'phoenix' to the similar but legally
    distinct 'fenix'.
