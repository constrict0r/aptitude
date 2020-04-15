Description
--------------------------------------------------------------

Ansible role to use as a wrapper for apt to manage packages.

This role performs the following actions:

- Ensure the requirements are installed.

- Ensure the current user can obtain administrative (root) permissions.

- Update the apt cache.

- If the **packages_purge** variable is defined, purge the packages listed on
  it.

- If the **configuration** variable is defined, purge the *packages_purge*
  listed on it.

- If the **packages** variable is defined, install the packages listed on it.

- If the **configuration** variable is defined, install the packages listed on
  it.