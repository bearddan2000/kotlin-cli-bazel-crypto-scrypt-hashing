load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_binary")

kt_jvm_binary (
    name = "BazelApp",
    srcs = glob(["kotlin/**/*.kt"]),
    main_class = "example.MainKt",
    deps = [
      "@maven//:javax_xml_bind_jaxb_api",
      "@maven//:org_mindrot_jbcrypt",
    ],
)
