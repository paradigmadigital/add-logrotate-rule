# add-logrotate-rule

Add logrotate rule

## Requirements

None

## Role Variables

* `program_name`: Name of the program, please avoid whitespaces :).
* `log_path`: Regexp to the logs, such as `/var/log/tor/*log`.
* `logrotate_options:` Dictionary of logrotate options, check the
  [defaults](defaults/main.yml) or `man logrotate` .

## Dependencies

None

## Example playbook

```yaml
- hosts: all
  roles:
    - add-logrotate-rule
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)
