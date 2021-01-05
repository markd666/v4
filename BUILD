load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_library(
    name = "defines_lib",
    hdrs = ["libs/definition.h"],
    visibility = ["//visibility:public"],
)

cc_binary(
    name = "main",
    srcs = ["main.cc", "device.cc", "device.h"],
    deps = [":defines_lib"],
   
    visibility = ["//visibility:public"],
)