# Copyright 2017 The Bazel Authors. All rights reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

load("@bazel_skylib//:bzl_library.bzl", "bzl_library")

package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # Apache 2.0

bzl_library(
    name = "docker",
    srcs = ["docker.bzl"],
)

bzl_library(
    name = "filetype",
    srcs = ["filetype.bzl"],
)

bzl_library(
    name = "label",
    srcs = ["label.bzl"],
)

bzl_library(
    name = "path",
    srcs = ["path.bzl"],
)

bzl_library(
    name = "zip",
    srcs = ["zip.bzl"],
)
