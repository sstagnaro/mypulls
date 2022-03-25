# mypulls

This playbook is intended to be run with ansible-pull on the control node where enterpirse playbook are executed.

The goal is to check against Git repos and pull them on a specific path in the control node.

### Usage:

	ansible-pull --url https://git.example.com/pull_prj

The above command can be scheduled in the crontab to perform periodic update checks.

N.B.: playbook name has to be left to `local.yml` or playbook name has to be specified.
