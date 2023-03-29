pyenv
=========

Installs and configures [pyenv](https://github.com/pyenv/pyenv) for the user.

Requirements
------------

The following collections are required:

- community.general

Role Variables
--------------

| Variable         | Default      | Description          |
| ---------------- | ------------ | -------------------- |
| pyenv\_repo\_dir | "/$HOME/opt" | Git repo destination |

Example Playbook
----------------

```yaml
- hosts: localhost
  roles:
     - role: whalej84.pyenv
       vars: pyenv_repo_dir: "/opt/pyenv"
```

