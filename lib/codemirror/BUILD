load("//lib/codemirror:cm.bzl", "pkg_cm")

# This library is only used to insert a license statement into
# js_licenses.txt.
java_library(
    name = "diff-match-patch",
    data = ["//lib:LICENSE-Apache2.0"],
    runtime_deps = ["@diff-match-patch//jar"],
)

pkg_cm()
