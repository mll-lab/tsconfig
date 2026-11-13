# [4.0.0](https://github.com/mll-lab/tsconfig/compare/v3.1.0...v4.0.0) (2026-11-13)


* feat!: resolve modules like a bundler and support TypeScript 6 and 7 ([#5](https://github.com/mll-lab/tsconfig/issues/5)) ([cb0d66e](https://github.com/mll-lab/tsconfig/commit/cb0d66ed80ac90576b2d960e97d82a738dbb342e))


### BREAKING CHANGES

* moduleResolution is bundler instead of node. A project
that relied on node's resolution, such as importing a path that a
package's exports field does not list, must set moduleResolution itself.

🤖 Generated with Claude Code

# [3.1.0](https://github.com/mll-lab/tsconfig/compare/v3.0.1...v3.1.0) (2025-11-04)


### Features

* migrate to OIDC for npm publishing ([c70d013](https://github.com/mll-lab/tsconfig/commit/c70d013b9d919055dba3e06a707ebcbfd2271248))

## [3.0.1](https://github.com/mll-lab/tsconfig/compare/v3.0.0...v3.0.1) (2023-11-23)


### Bug Fixes

* add release.config.js ([1c4c5f9](https://github.com/mll-lab/tsconfig/commit/1c4c5f98c4431a41379b8816fea8f2d5c1d30bd8))
