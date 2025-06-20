# steamos-finalize-install

> Complete a SteamOS installation by setting up bootloaders and applying system updates.
> More information: <https://gitlab.com/users/evlaV/projects>.

- Finalize the installation with default behavior:

`sudo steamos-finalize-install`

- Finalize without updating bootloaders or kernel:

`sudo steamos-finalize-install --no-bootloaders --no-kernel`

- Skip all migration steps:

`sudo steamos-finalize-install --no-migrate`

- Set a specific root hash during finalization:

`sudo steamos-finalize-install --roothash {{hash}}`

- Force migration steps outside of a chroot environment:

`sudo steamos-finalize-install --force`
