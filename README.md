# ansible-pull-example

> code base for ansible-pull: <https://github.com/ansible/ansible/blob/devel/lib/ansible/cli/pull.py>.

Just an example for ansible-pull

## Command to run ansible-pull from this repo

```bash
ansible-pull -U https://github.com/nsuthison/ansible-pull-example.git -C main -i hosts local.yaml
```

Note: Default playbook for ansible-pull is _local.yml_. In this repo, I use _local.y*a*ml_ instead so I need to specific the playbook name param.
