pre-commit Robot Framework Lint wrapper
==============================

This is a [pre-commit](https://github.com/pre-commit) hook that will run
the [Robot Framework Lint tool](https://github.com/boakley/robotframework-lint) on all of your robot files.

* [pre-commit](https://github.com/pre-commit)
* [Robot Framework](https://robotframework.org)


Add this to your ``.pre-commit-config.yaml`` file

    -   repo: git://github.com/guykisel/pre-commit-robotframework-lint
        sha: 04770a44648d3697a3fc974dff212c4be7d3ed88
        hooks:
        -   id: robotframework-lint
