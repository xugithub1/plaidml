# Copyright 2020 Intel Corporation

package(default_visibility = ["//visibility:public"])

load("//bzl:plaidml.bzl", "plaidml_cc_library")

plaidml_cc_library(
    name = "tile_to_pxa",
    srcs = glob(["*.cc"]),
    hdrs = glob(["*.h"]),
    tags = ["llvm"],
    deps = [
        "//pmlc/dialect/pxa/ir",
        "//pmlc/dialect/tile/ir",
        "//pmlc/dialect/tile/transforms",
    ],
    alwayslink = 1,
)
