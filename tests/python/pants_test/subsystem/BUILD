# Copyright 2015 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_tests(
  sources=['test_subsystem.py'],
  dependencies=[
    'src/python/pants/option',
    'src/python/pants/subsystem',
    'src/python/pants/testutil:test_base',
  ],
)

python_library(
  name='subsystem_utils',
  sources=['subsystem_util.py'],
  dependencies=[
    'src/python/pants/testutil/subsystem',
    'tests/python/pants_test:deprecated_testinfra',
  ],
)
