# Docker

Role to install Idea IntelliJ on an Ubuntu box

## Requirements

After downloading the role use the url on `eclipse/files/ideaIU-2016.1.2b.tar.gz.download` to download the installer and make sure its name matches the variable `INTELLIJ_BUNDLE`.

##Role Variables

 * `INTELLIJ_BUNDLE` - the eclipse bundle version, defaults to `ideaIU-2016.1.2b.tar.gz`.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: intellij-idea, INTELLIJ_BUNDLE: ideaIU-2016.1.2b.tar.gz }

## License

MIT

## Author Information

Marco Shimomoto
