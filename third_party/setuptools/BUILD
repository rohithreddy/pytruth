# Copyright 2017 Google Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

licenses(["notice"])  # MIT

exports_files(["LICENSE"])

py_library(
    name = "setuptools",
    srcs = glob([
        "pkg_resources/**/*.py",
        "setuptools/**/*.py",
    ]),
    visibility = ["//visibility:public"],
    deps = [
        "@appdirs_1_4_3//:appdirs",
        "@pyparsing_2_3_1//:pyparsing",
    ],
)
