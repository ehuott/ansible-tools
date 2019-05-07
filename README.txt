README for "ansible-tools" Project Directory

This project is intended as a kind of Ansible toolbox.

Here's what there is so far (not much):

* roles/backup-file-maker:

  A role making a dated backup file of a specified target file.

* make-backup-file.yml:

  An importable playbook to make a dated backup of a specified target file. Playbook behavior can be controlled by pre-defining certain variables.

* make-backup-file-tasks.xml

  An importable task list to make a dated backup of a specified target file. Simpler and more flexible than the role implementation. It can be invoked from within a role.


# Emacs variables below this line
# Local Variables:
# mode:visual-line
# End:
