repository/ is a maven repository with dependencies needed
to compile tools/base, tools/swt and tools/buildSrc
without accessing an external repository.

Dependency that are put in there that also get shipped with
the SDK Tools much include a NOTICE file next to the artifact
or the build will fail.
