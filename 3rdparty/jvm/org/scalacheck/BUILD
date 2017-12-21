load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")
scala_library(
    name = "scalacheck",
    exports = [
        "//external:jar/org/scalacheck/scalacheck_2_11"
    ],
    runtime_deps = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_sbt:test_interface"
    ],
    visibility = [
        "//visibility:public"
    ]
)


