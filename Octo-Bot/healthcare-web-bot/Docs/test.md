# Tests
There are 2 types of tests that can be run for `healthcare-web-bot`, namely tests with Firefox interface UI and tests without Firefox interface UI

### Running tests with Firefox interface UI (It requires a desktop terminal)
```console
joelczk@OctoBot/Octo-Bot/<bot-name>/test:~/OctoBot$ python3 TestUI.py
```

### Running tests without Firefox interface UI (It does not require a desktop terminal)
```console
joelczk@OctoBot/Octo-Bot/<bot-name>:~/OctoBot$ python3 TestNoUI.py
```

By default, `test.sh` file runs both tests with and without Firefox interface UI (It requires a desktop terminal for this)