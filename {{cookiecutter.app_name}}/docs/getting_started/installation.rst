Installation
============

{{cookiecutter.app_full_name}}


Install from github:

```
pip install -e http://github.com/{{cookiecutter.github_username}}/{{cookiecutter.app_name}}
```


Running the app
===============

Do a dry-run first (`-n`) and simply print (`-p`) what would be run:

```
{{cookiecutter.app_name}} /path/to/bids/dir /path/to/output/dir participant -np
```

Run the app, using all cores:

```
{{cookiecutter.app_name}} /path/to/bids/dir /path/to/output/dir participant --cores all
```

If any workflow rules require containers, then run with the `--use-singularity`` option.




