# RHEL 9 Workstation

This playbook is intended to be run with `ansible-pull` just after teh RHEL 9 installation is completed.

The goal is to provision a workstation with the desired packages and configurations.

### Usage:

	ansible-pull --url https://git.example.com/workstation_rhel9

The above command can be scheduled in the crontab to perform periodic update checks.

N.B.: playbook name has to be left to `local.yml` or playbook name has to be specified.
