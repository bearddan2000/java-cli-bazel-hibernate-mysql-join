java_binary (
    name = "BazelApp",
    srcs = glob(["java/**/*.java"]),
    main_class = "example.Main",
    deps = [
      "@maven//:log4j_log4j",
"@maven//:org_slf4j_slf4j_api",
"@maven//:org_slf4j_slf4j_log4j12",
"@maven//:org_postgresql_postgresql",
"@maven//:org_hibernate_hibernate_core",
"@maven//:jakarta_xml_bind_jakarta_xml_bind_api",
"@maven//:org_glassfish_jaxb_jaxb_runtime"
    ],
    resources = [
      "resources/log4j.xml",
      "resources/hibernate.cfg.xml"
    ],    
    visibility = ["//visibility:public"],
)
