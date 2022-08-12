CHANGELOG
=========

v1.6 - unreleased
----

- Changed login shell to /bin/bash for user "ubuntu" [fixes #1]

v1.5
----

- create-image.sh, create-64bit-image.sh: New scripts
- Changed image names: Added architecture
- Renamed: lxc-ubuntu-32bit -> lxc-ubuntu-i686-amd64

v1.4
----

- build.sh: New script
- install.sh: New script
- Added "logrotate"
- Use xz compression

v1.3
----

- Set hostname to container name
- Remove isc-dhcp-client

v1.2
----

- Added lots of debs, for example "sudo"
- Added user "ubuntu"

v1.1
----

- Added description for focal debs
- Use freshly created focal debs

v1.0
----

- Created images for Ubuntu-20.04 (focal) and 22.04 (jammy)
- Added description on how to build missing debs
- Added screenshort from virustotal

v0.5
----

- Reduced image size

v0.4
----

- Fixed naming issues

v0.3
----

- Created exported LXC image

v0.2
----

- Some initial work related to Ubuntu-20.04 (focal)

v0.1
----

- A first release (experimental)