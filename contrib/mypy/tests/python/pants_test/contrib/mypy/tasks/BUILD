# Copyright 2017 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_tests(
  name='mypy',
  source = 'test_mypy.py',
  dependencies=[
    'src/python/pants/testutil:task_test_base',
    'contrib/mypy/src/python/pants/contrib/mypy/tasks',
  ],
)

python_tests(
  name='mypy_integration',
  sources=['test_mypy_integration.py'],
  dependencies=[
    'src/python/pants/testutil:int-test',
    'contrib/mypy:examples_directory',
  ],
  tags={'integration'},
  timeout = 120,
)
