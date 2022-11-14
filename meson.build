project('lz-end-toolkit', 'cpp')
subdir('extras')

inc = include_directories('include')

executable('decode', 'src/main_decode.cpp', 'src/utils.cpp',
  include_directories: inc)
executable('parse', 'src/main_parse.cpp', 'src/utils.cpp',
  include_directories: inc)
executable('verify', 'src/main_verify.cpp', 'src/utils.cpp',
  include_directories: inc)
