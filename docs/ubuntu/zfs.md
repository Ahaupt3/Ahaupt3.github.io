# ZFS

 After installing Ubuntu with ZFS, run via CLI.

 Create Pool - Mirroring

* `sudo zpool create ub-pool mirror /dev/sdx /dev/sdx`
* `sudo zpool status ub-pool`

Create Snapshots

* `zfs list`
* `sudo zfs snapshot <rpool>@<snapshot name>`

Restore from Snapshots

* `sudo zfs rollback <rpool>@<snapshot name>`
