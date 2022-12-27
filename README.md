# mypulls

Various playbooks intended to be used with `ansible-pull`.

### Usage:

	ansible-pull --url https://git.example.com/pull_prj

The above command can be scheduled in the crontab to perform periodic update checks.

N.B.: playbook name has to be left to `local.yml` or playbook name has to be specified.
