java_binary(
    srcs = ["Hello.java"],
    main_class = "main.java.com.example.project.Hello",
    name = "hello_world",
    deps = [
        ":util_lib"
    ],
)

java_library(
    name = "util_lib",
    srcs = glob(["utils/*.java"]),
    visibility = ["//visibility:public"],
)


# bazel build //src/main/java/com/example/project:hello_world
# bazel run //src/main/java/com/example/project:hello_world