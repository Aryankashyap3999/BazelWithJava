java_library(
    name = "project_lib",
    srcs = glob(["*.java"]),
    visibility = ["//visibility:public"],
)

java_binary(
    name = "hello_world",
    srcs = ["Hello.java"],
    main_class = "main.java.com.example.project.Hello",
    deps = [":project_lib"],
)
