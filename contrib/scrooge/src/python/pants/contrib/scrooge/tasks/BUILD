# Copyright 2015 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_library(
  dependencies=[
    ':scrooge_gen',
    ':thrift_linter',
  ],
)

python_library(
  name='scrooge_gen',
  sources=['scrooge_gen.py'],
  dependencies=[
    ':java_thrift_library_fingerprint_strategy',
    ':thrift_util',
    '3rdparty/python/twitter/commons:twitter.common.collections',
    'src/python/pants/backend/codegen/thrift/java',
    'src/python/pants/backend/jvm/targets:java',
    'src/python/pants/backend/jvm/targets:scala',
    'src/python/pants/backend/jvm/tasks:jvm_tool_task_mixin',
    'src/python/pants/backend/jvm/tasks:nailgun_task',
    'src/python/pants/base:build_environment',
    'src/python/pants/base:exceptions',
    'src/python/pants/build_graph',
    'src/python/pants/option',
    'src/python/pants/task',
    'src/python/pants/util:dirutil',
    'src/python/pants/util:memo',
  ],
  tags = {"partially_type_checked"},
)

python_library(
  name='thrift_linter',
  sources=['thrift_linter.py'],
  dependencies=[
    ':thrift_util',
    'src/python/pants/backend/codegen/thrift/java',
    'src/python/pants/backend/jvm/tasks:nailgun_task',
    'src/python/pants/base:exceptions',
    'src/python/pants/base:worker_pool',
    'src/python/pants/base:workunit',
    'src/python/pants/option',
    'src/python/pants/task'
  ],
)

python_library(
  name='thrift_util',
  sources=['thrift_util.py'],
  tags = {"partially_type_checked"},
)

python_library(
  name='java_thrift_library_fingerprint_strategy',
  sources=['java_thrift_library_fingerprint_strategy.py'],
  dependencies=[
    'src/python/pants/backend/codegen/thrift/java',
    'src/python/pants/base:fingerprint_strategy',
  ],
  tags = {"partially_type_checked"},
)
