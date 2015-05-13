# Digital Ocean Drupal secure script

- Adds a webadmin user+group
- Sets the Drupal code base to be owned by a regular user (not www-data!)
- Sets the sites/default/files/ with stickybit and owned by www-data

Whilst playing with a Digital Ocean Drupal image instance I discovered that the permissions are not really all that secure (WYSIWYG editors have a long history of allowing various attacks)

Note: I'm quite new to Ansible
