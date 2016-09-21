#### ansible-fileman project
Managing files with dah great Ansible ! :neckbeard:
This project (like all of my Ansible projects) follow the [best practices guide][1]
from the official Ansible documentation.

:warning: This repo is for testing file management with ansible,
it's no official project at all...

The operations that you'll see around here:
- moving folders from one place to another
- filtering folders older than a period of time
- symlinking folders back from where they were moved (or somewhere else)
- :new: DigitalOcean integration

> shortly ... just some folder operations to automate things.

##### In which context can I use this?
> You can use this whenever you're working with large data, and want to move
folders older than 3 months + (let's assume) in a directory that has
[Replication Factor 1][2] to save some space on the Disk.

##### Resources
- [digital ocean module][3]

[1]: https://docs.ansible.com/ansible/playbooks_best_practices.html
[2]: http://docs.splunk.com/Documentation/Splunk/6.4.3/Indexer/Thereplicationfactor
[3]: https://docs.ansible.com/ansible/digital_ocean_module.html