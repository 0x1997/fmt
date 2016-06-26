project('fmt', 'cpp')

inc = include_directories('.', is_system: true)

install_headers(
    'fmt/container.h',
    'fmt/format.h',
    'fmt/ostream.h',
    'fmt/posix.h',
    'fmt/printf.h',
    'fmt/string.h',
    'fmt/time.h',
    subdir: 'fmt'
)

lib = static_library('fmt',
    'fmt/format.cc',
    'fmt/ostream.cc',
    'fmt/posix.cc',
    'fmt/printf.cc',
    pic: true,
)
