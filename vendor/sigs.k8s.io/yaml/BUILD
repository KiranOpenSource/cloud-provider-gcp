load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "yaml",
    srcs = [
        "fields.go",
        "yaml.go",
        "yaml_go110.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/sigs.k8s.io/yaml",
    importpath = "sigs.k8s.io/yaml",
    visibility = ["//visibility:public"],
    deps = ["//vendor/gopkg.in/yaml.v2:yaml_v2"],
)
