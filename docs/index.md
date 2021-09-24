# iso-profile
# ISO profile for Woof OS
ISO profile for building Woof OS using [`archiso`](https://wiki.archlinux.org/title/Archiso)

## Building the ISO profile into an ISO

**WARNING:** This ISO profile has not been tested yet and I will **not** recommend you directly build and use the ISO image on an actual machine. Use a Virtual Machine instead.

If you are on an Arch based system, you can install `archiso` with `sudo pacman -S archiso`.
I'm not sure if you can build this profile on other distributions. Usually impossible.

After installing `archiso`,
- Clone this repository
`git clone https://github.com/woof-os/iso-profile`

- CD into the directory
`cd iso-profile`

- Build the ISO
`mkarchiso -v ./archlive`

Now, you can test the iso on your virtual machine.

