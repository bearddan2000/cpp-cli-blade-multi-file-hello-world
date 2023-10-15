cc_library(
    name = 'lib',
    srcs = 'greeting.cpp',
    hdrs = 'greeting.h',
)

cc_binary(
    name = 'BladeApp',
    srcs = 'main.cpp',
    deps = [':lib']
)