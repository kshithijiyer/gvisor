load("@io_bazel_rules_go//go:def.bzl", "go_library")

package(licenses = ["notice"])

go_library(
    name = "gtest",
    srcs = ["gtest.go"],
    importpath = "gvisor.dev/test/syscalls/gtest",
    visibility = [
        "//test:__subpackages__",
    ],
)
