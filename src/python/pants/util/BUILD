# Copyright 2014 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_library(
  name = 'argutil',
  sources = ['argutil.py'],
  tags = {'type_checked'},
)

python_library(
  name = 'contextutil',
  sources = ['contextutil.py'],
  dependencies = [
    '3rdparty/python:ansicolors',
    ':dirutil',
    ':tarutil',
  ],
  tags = {'type_checked'},
)

python_library(
  name = 'collections',
  sources = ['collections.py'],
  tags = {'type_checked'},
)

python_library(
  name = 'desktop',
  sources = ['desktop.py'],
  dependencies = [
    ':osutil',
  ],
  tags = {'type_checked'},
)

python_library(
  name = 'dirutil',
  sources = ['dirutil.py'],
  dependencies = [
    ':strutil',
    '3rdparty/python:typing-extensions',
  ],
  tags = {'type_checked'},
)

python_library(
  name = 'eval',
  sources = ['eval.py'],
  tags = {'type_checked'},
)

python_library(
  name = 'fileutil',
  sources = ['fileutil.py'],
  dependencies = [
    ':contextutil',
  ],
  tags = {'type_checked'},
)

python_library(
  name = 'filtering',
  sources = ['filtering.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'memo',
  sources = ['memo.py'],
  dependencies = [
    ':meta'
  ],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'meta',
  sources = ['meta.py'],
  dependencies = [
    '3rdparty/python:dataclasses'
  ],
  tags = {'type_checked'},
)

python_library(
  name = 'netrc',
  sources = ['netrc.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'objects',
  sources = ['objects.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'osutil',
  sources = ['osutil.py'],
  tags = {'type_checked'},
)

python_library(
  name = 'process_handler',
  sources = ['process_handler.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'retry',
  sources = ['retry.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'rwbuf',
  sources = ['rwbuf.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 's3_log_aggregator',
  sources = ['s3_log_aggregator.py'],
  dependencies = [
    '3rdparty/python:s3logparse'
  ],
)

python_binary(
  name = 's3_log_aggregator_bin',
  entry_point = 'pants.util.s3_log_aggregator',
  dependencies = [
    ':s3_log_aggregator'
  ],
)

python_library(
  name = 'socket',
  sources = ['socket.py'],
  tags = {'partially_type_checked'},
)

python_library(
  name = 'strutil',
  sources = ['strutil.py'],
  tags = {'type_checked'},
)

python_library(
  name = 'tarutil',
  sources = ['tarutil.py'],
  tags = {'type_checked'},
)

python_library(
  name = 'xml_parser',
  sources = ['xml_parser.py'],
  tags = {'partially_type_checked'},
)
