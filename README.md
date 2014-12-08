pre-commit Robot Framework Lint wrapper
==============================

This is a [pre-commit](https://github.com/pre-commit) hook that will run
the [Robot Framework Lint tool](https://github.com/boakley/robotframework-lint) on all of your robot files.

* [pre-commit](https://github.com/pre-commit)
* [Robot Framework](https://robotframework.org)


Add this to your ``.pre-commit-config.yaml`` file

  -   repo: git://github.com/guykisel/pre-commit-robotframework-lint
      sha: cf9f417643917f2fdaa0f30d5c0e1d0597cfe40f
      hooks:
      -   id: robotframework-lint

Development: ``pip install -r requirements-dev.txt``
