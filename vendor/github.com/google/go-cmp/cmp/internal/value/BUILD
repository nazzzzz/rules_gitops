load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "name.go",
        "pointer.go",
        "sort.go",
    ],
    importmap = "github.com/fasterci/rules_gitops/vendor/github.com/google/go-cmp/cmp/internal/value",
    importpath = "github.com/google/go-cmp/cmp/internal/value",
    visibility = ["//vendor/github.com/google/go-cmp/cmp:__subpackages__"],
)
