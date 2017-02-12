# rules for scala
# https://github.com/bazelbuild/rules_scala#getting-started
# pull rule definitions from git

BAZEL_VERSION = "1f49b6befa57e5cea819d5010785a90fc5bd0db6"

git_repository(
    name = "io_bazel_rules_scala",
    remote = "https://github.com/bazelbuild/rules_scala.git",
    commit = "f84438d39862c97ba037d28c0b6a606db8fabbde", # update this as needed
)

# load the desired scala rules for this workspace
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_repositories")
scala_repositories()
