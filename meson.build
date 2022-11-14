project('lz-end-toolkit', 'cpp')

inc = include_directories('include')

executable('decode', 'src/main_decode.cpp', 'src/utils.cpp',
  include_directories: inc)
executable('parse', 'src/main_parse.cpp', 'src/utils.cpp',
  include_directories: inc)
executable('verify', 'src/main_verify.cpp', 'src/utils.cpp',
  include_directories: inc)

# In-Ram-Parser
inramparser = static_library('in-ram-parser', 'extras/in-ram-parser/src/utils.cpp')

inramparser_dep = declare_dependency(
  include_directories: include_directories('extras/in-ram-parser/include'),
  sources: 'extras/in-ram-parser/src/utils.cpp',
  link_with: inramparser
)
