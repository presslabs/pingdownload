pingdownload
===
An utility script to download your pingdom data for archival.


Installation
---
`pingdownload` requires `python` and
[`requests`](http://docs.python-requests.org/en/master/user/install/#install)
module.


Usage
---
```
usage: pingdownload [-h] -u USER -p PASSWORD -k KEY
                  (-a | -i CHECK_ID [CHECK_ID ...]) [--from-id FROM_ID]
                  [--debug]

Download pingdom data

optional arguments:
  -h, --help            show this help message and exit
  -u USER, --user USER  Pingdom username
  -p PASSWORD, --password PASSWORD
                        Pingdom password
  -k KEY, --key KEY     Pingdom application key
  -a, --all             Backup all checks
  -i CHECK_ID [CHECK_ID ...], --check-id CHECK_ID [CHECK_ID ...]
                        Pingdom check ids to download data for
  --from-id FROM_ID     Archive checks with id greater than this id
  --debug               Enable debug messages

```


License
---

This project is licensed under Apache 2.0 license. Read the [LICENSE](LICENSE)
file in the top distribution directory for the full license text.
