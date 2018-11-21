ansible-wizzy [![Build Status](https://travis-ci.org/krzyzakp/ansible-wizzy.svg?branch=master)](https://travis-ci.org/krzyzakp/ansible-wizzy)
=========

Ansible role for installing and configuring Wizzy - CLI for managing Grafana


## Role variables
```
wizzy_url: http:/127.0.0.1:3000      # URL to Grafana instance
wizzy_username: admin                # Username to access Grafana
wizzy_username: admin                # Password for Grafana user
```

## Testing
Tests are done using [docker_test_runner](https://github.com/timorunge/docker-test-runner), thanks to [Timo Runge](https://github.com/timorunge/docker-test-runner). You can run them locally, before commiting. Fetch [docker_test_runner.py](https://github.com/timorunge/docker-test-runner/blob/master/docker_test_runner.py) into main app dir (it's in _.gitignore_ file already) and run it.

## License
BSD


## Author information
Created by [krzyzakp](https://github.com/krzyzakp)
