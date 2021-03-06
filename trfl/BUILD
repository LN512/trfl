licenses(["notice"])  # Apache 2.0 License

package(default_visibility = ["//visibility:public"])

exports_files([
    "LICENSE",
    "setup.py",
])

# Placeholder for internal Python version compatibility macro.

py_library(
    name = "trfl",
    srcs = ["__init__.py"],
    deps = [
        ":action_value_ops",
        ":base_ops",
        ":discrete_policy_gradient_ops",
        ":dist_value_ops",
        ":dpg_ops",
        ":indexing_ops",
        ":pixel_control_ops",
        ":policy_gradient_ops",
        ":retrace_ops",
        ":sequence_ops",
        ":value_ops",
        ":vtrace_ops",
    ],
)

py_library(
    name = "action_value_ops",
    srcs = ["action_value_ops.py"],
    deps = [
        ":base_ops",
        ":indexing_ops",
        ":sequence_ops",
        # tensorflow dep,
    ],
)

py_library(
    name = "base_ops",
    srcs = ["base_ops.py"],
    deps = [
        # six dep,
        # tensorflow dep,
    ],
)

py_library(
    name = "discrete_policy_gradient_ops",
    srcs = ["discrete_policy_gradient_ops.py"],
    deps = [
        ":base_ops",
        ":value_ops",
        # six dep,
        # tensorflow dep,
    ],
)

py_library(
    name = "dist_value_ops",
    srcs = ["dist_value_ops.py"],
    deps = [
        ":base_ops",
        # tensorflow dep,
    ],
)

py_library(
    name = "dpg_ops",
    srcs = ["dpg_ops.py"],
    deps = [
        ":base_ops",
        # tensorflow dep,
    ],
)

py_library(
    name = "indexing_ops",
    srcs = ["indexing_ops.py"],
    deps = [
        # tensorflow dep,
    ],
)

py_library(
    name = "pixel_control_ops",
    srcs = ["pixel_control_ops.py"],
    deps = [
        ":action_value_ops",
        ":base_ops",
        # sonnet dep,
        # tensorflow dep,
    ],
)

py_library(
    name = "policy_gradient_ops",
    srcs = ["policy_gradient_ops.py"],
    deps = [
        ":base_ops",
        ":value_ops",
        # six dep,
        # tensorflow dep,
    ],
)

py_library(
    name = "retrace_ops",
    srcs = ["retrace_ops.py"],
    deps = [
        ":base_ops",
        ":indexing_ops",
        ":sequence_ops",
        # six dep,
        # tensorflow dep,
    ],
)

py_library(
    name = "sequence_ops",
    srcs = ["sequence_ops.py"],
    deps = [
        # tensorflow dep,
    ],
)

py_library(
    name = "value_ops",
    srcs = ["value_ops.py"],
    deps = [
        ":base_ops",
        ":sequence_ops",
        # tensorflow dep,
    ],
)

py_library(
    name = "vtrace_ops",
    srcs = ["vtrace_ops.py"],
    deps = [
        # tensorflow dep,
    ],
)

py_test(
    name = "action_value_ops_test",
    srcs = ["action_value_ops_test.py"],
    deps = [
        ":action_value_ops",
        # numpy dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "discrete_policy_gradient_ops_test",
    srcs = ["discrete_policy_gradient_ops_test.py"],
    deps = [
        ":discrete_policy_gradient_ops",
        # absl/testing:parameterized dep,
        # numpy dep,
        # six dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "dist_value_ops_test",
    srcs = ["dist_value_ops_test.py"],
    deps = [
        ":dist_value_ops",
        # numpy dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "dpg_ops_test",
    srcs = ["dpg_ops_test.py"],
    deps = [
        ":dpg_ops",
        # numpy dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "indexing_ops_test",
    srcs = ["indexing_ops_test.py"],
    deps = [
        ":indexing_ops",
        # tensorflow dep,
    ],
)

py_test(
    name = "pixel_control_ops_test",
    srcs = ["pixel_control_ops_test.py"],
    deps = [
        ":pixel_control_ops",
        # numpy dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "policy_gradient_ops_test",
    srcs = ["policy_gradient_ops_test.py"],
    deps = [
        ":policy_gradient_ops",
        # absl/testing:parameterized dep,
        # numpy dep,
        # six dep,
        # tensorflow dep,
        # tensorflow_probability dep,
    ],
)

py_test(
    name = "retrace_ops_test",
    srcs = ["retrace_ops_test.py"],
    deps = [
        ":retrace_ops",
        # numpy dep,
        # six dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "sequence_ops_test",
    srcs = ["sequence_ops_test.py"],
    deps = [
        ":sequence_ops",
        # numpy dep,
        # six dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "value_ops_test",
    srcs = ["value_ops_test.py"],
    deps = [
        ":value_ops",
        # absl/testing:parameterized dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "vtrace_ops_test",
    srcs = ["vtrace_ops_test.py"],
    deps = [
        ":vtrace_ops",
        # absl/testing:parameterized dep,
        # numpy dep,
        # tensorflow dep,
    ],
)
