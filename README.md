# Oracle Repository

Add Oracle Repository

This role is designed to add the Oracle Repository to RedHat.

_Note: It would be far better to use a RedHat subscription registration, but_
_for, at least, testing purposes, this can provide some easier automation._

## Requirements

RedHat Enterprise Linux 6/7

### Example Playbooks

Designed to be used as a dependency for other 'jamf' roles. However, a simple
playbook could be used to run it standalone.

    - hosts: all
      tasks:
      - import_role:
          name: kaos2oak.oracle-repo

## License

MIT

## Author Information

Justin Sako
