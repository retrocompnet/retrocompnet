# retrocomp.network

This is the top level repository. All other repositories are
submodules, so when you check this out, be sure you do an initial

```
$ git submodule update --init --recursive
```

Before you really get deep.

This repo is structured as a monorepo with submodules using the Bazel
build system to orchestrate it all together. You will want to install
`bazelisk` locally before you try to build.
