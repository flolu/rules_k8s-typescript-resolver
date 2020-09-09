# Custom rules_k8s resolver with Typescript

## Issue

[rules_k8s][0] has a [good exmaple][1] for using custom resolvers with Go.

My goal is to implement a custom resolver with Typescript and Node.js.
I've replicated the example. But running the Node.js binary fails:

```
ERROR: cannot find build_bazel_rules_nodejs/third_party/github.com/bazelbuild/bazel/tools/bash/runfiles/runfiles.bash
```

## Setup

Try it yourself by cloning this repository and then running

```
yarn install
yarn start
```

[0]: https://github.com/bazelbuild/rules_k8s
[1]: https://github.com/bazelbuild/rules_k8s/tree/master/examples/resolver
