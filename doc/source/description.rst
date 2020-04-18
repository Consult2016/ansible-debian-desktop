Description
--------------------------------------------------------------

Ansible role to setup Debian-like systems desktop configuration.

This is capable of:

- Upgrade the system.

- Add `apt <https://wiki.debian.org/Apt>`_ repository sources.

- Update the apt cache.

- Uninstall apt packages.

- Install apt packages.

- Install `yarn <https://yarnpkg.com>`_ packages.

- Install `pip <https://pypi.org/project/pip/>`_ packages.

- Apply system-wide configuration using git.

- Stop services and disable them.

- Enable services and restart them.

- Create users.

- Add users to groups.

- Apply user-wide configuration using git.

- Run custom user tasks.

By default this role applies the following configuration:

- Installs the base software:

 .. include:: part/package/base.inc

- Installs the desktop software:

 .. include:: part/package/desktop.inc

- Configures the base software:

 .. include:: part/configured/base.inc

- Configures the desktop software:

 .. include:: part/configured/desktop.inc