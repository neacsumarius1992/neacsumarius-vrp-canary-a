# neacsumarius_vrp_canary_a

Harmless Bazel module used as a reporter-controlled production canary for the
Google OSS VRP validation requested in report `569037834`.

The module exposes the public target `//:canary`, which contains a static text
file. It performs no command execution and no network access.
