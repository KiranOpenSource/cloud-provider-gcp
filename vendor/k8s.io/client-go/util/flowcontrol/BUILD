load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "flowcontrol",
    srcs = [
        "backoff.go",
        "throttle.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/util/flowcontrol",
    importpath = "k8s.io/client-go/util/flowcontrol",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/time/rate",
        "//vendor/k8s.io/utils/clock",
        "//vendor/k8s.io/utils/clock/testing",
        "//vendor/k8s.io/utils/integer",
    ],
)
