#   //src/main/java/com/example/project:hello_world_lib

java_library(
  name =  "hello_lib",
  srcs = glob(["*.java"]),
  visibility = ["//visibility:public"],
)




#   //src/main/java/com/example/project:hello

java_binary(
  name= "hello",
  srcs = ["HelloWorld.java"],
  main_class = "main.java.com.example.project.HelloWorld",
  runtime_deps = [":hello_lib"],
)

