# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-08-27)

<section class="features">

### Features

-   [`3656652`](https://github.com/stdlib-js/stdlib/commit/36566524e333dabea3b4b47c00b154accc1c2c23) - add `math/base/special/lucasf` [(#6223)](https://github.com/stdlib-js/stdlib/pull/6223)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`d109efc`](https://github.com/stdlib-js/stdlib/commit/d109efcbb6b3f13f6ca8dfba7bde7a07a1d27614): update signature to accept floats

    -   User code should behave similarly in the primary case of providing integer-valued input values. However, no longer will real-values truncate. Now, real-valued inputs will result in `NaN`, which is, arguably, better behavior, as real-to-integer truncation can be a source of silent bugs.

</section>

<!-- /.breaking-changes -->

<section class="issues">

### Closed Issues

This release closes the following issue:

[#6712](https://github.com/stdlib-js/stdlib/issues/6712)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`81f904d`](https://github.com/stdlib-js/stdlib/commit/81f904da25808197e2ae83ebf9c8b26860855e7c) - **bench:** fix failing C benchmarks by using `round` and `roundf` [(#7980)](https://github.com/stdlib-js/stdlib/pull/7980) _(by Gunj Joshi)_
-   [`d109efc`](https://github.com/stdlib-js/stdlib/commit/d109efcbb6b3f13f6ca8dfba7bde7a07a1d27614) - **refactor:** modify C implementation to accept `float` instead of `int32` in `math/base/special/lucasf` [(#7939)](https://github.com/stdlib-js/stdlib/pull/7939) _(by Gunj Joshi)_
-   [`8b784ff`](https://github.com/stdlib-js/stdlib/commit/8b784ff130dfd2f8fdb5e60f5ac0e9ef7450bb66) - **chore:** address commit comments for commit `3656652` [(#6783)](https://github.com/stdlib-js/stdlib/pull/6783) _(by devshree-bhati)_
-   [`3656652`](https://github.com/stdlib-js/stdlib/commit/36566524e333dabea3b4b47c00b154accc1c2c23) - **feat:** add `math/base/special/lucasf` [(#6223)](https://github.com/stdlib-js/stdlib/pull/6223) _(by Harsh, stdlib-bot, Karan Anand)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 4 people contributed to this release. Thank you to the following contributors:

-   Gunj Joshi
-   Harsh
-   Karan Anand
-   devshree-bhati

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

