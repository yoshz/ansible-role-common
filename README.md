common
======

An Ansible role for common system configuration:

  - Fix ns resolving when necessary
  - Configure default locale
  - Build additional locales
  - Install system packages
  - Install ruby gems
  - Setup default gitconfig when git is installed


Requirements
------------

None


Role Variables
--------------

Set locales:

    locale_default: "en_US.UTF-8"
    locale_install: [ "en_US.UTF-8", "nl_NL.UTF-8" ]

Install system packages:

    packages:
      - curl
      - vim
      - htop
      - atop


Dependencies
------------

None


License
-------

MIT
