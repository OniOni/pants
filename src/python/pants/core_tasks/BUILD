# Copyright 2015 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_library(
  dependencies=[
    '3rdparty/python:ansicolors',
    '3rdparty/python:packaging',
    '3rdparty/python:setuptools',
    ':templates',
    'src/python/pants/auth',
    'src/python/pants/base:build_environment',
    'src/python/pants/base:deprecated',
    'src/python/pants/base:exceptions',
    'src/python/pants/base:generator',
    'src/python/pants/base:revision',
    'src/python/pants/base:workunit',
    'src/python/pants/build_graph',
    'src/python/pants/goal',
    'src/python/pants/goal:task_registrar',
    'src/python/pants/help',
    'src/python/pants/option',
    'src/python/pants/pantsd:process_manager',
    'src/python/pants/reporting',
    'src/python/pants/source',
    'src/python/pants/task',
    'src/python/pants/util:contextutil',
    'src/python/pants/util:desktop',
    'src/python/pants/util:dirutil',
    'src/python/pants:version',
  ],
)

resources(
  name='templates',
  sources=globs('templates/**/*.mustache'),
)
