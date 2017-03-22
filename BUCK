cxx_library(
  name = 'immutable-cpp',
  header_namespace = 'immutable',
  exported_headers = subdir_glob([
    ('immutable', '**/*.h'),
  ]),
  srcs = glob([
    'immutable/**/*.cc',
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
)
