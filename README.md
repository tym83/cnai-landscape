# CNAI Landscape

CNAI landscape generated with [cncf/landscape2](https://github.com/cncf/landscape2).


To add or correct landscape entries.

* fork/PR
* make changes
* submit

Once we are far enough (tbd) we will take this work and submit to integrate with original landscape.

Below are original instructions to help set this up (by Sergio).

- The `main` branch contains the output of the `landscape2 new` command.
- The `build` branch contains the output of the `landscape2 build` command, which is served by GitHub Pages at <https://rx-m.github.io/cnai-landscape>.
- The [build workflow](https://github.com/rx-m/cnai-landscape/blob/main/.github/workflows/build.yml) builds the landscape and pushes the result to the `build` branch on every push to the `main` branch.

Also modified:

```
# base_path: /<BASE_PATH>
#
base_path: /cnai-landscape
```