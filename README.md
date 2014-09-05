## composer [![Build Status](https://travis-ci.org/Oefenweb/ansible-composer.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-composer)

Set up composer.

#### Requirements

* `curl`
* `php` (5.3.2+)

#### Variables

* `composer_install_dir` [default: `/usr/local/bin`]: Install directory

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - composer
```

#### License

MIT

#### Author Information

Mischa ter Smitten (based on work of Vinelab)

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-composer/issues)!
