# Bazel CI dashboard

Status of the `Bazel CI` workflow (`.github/workflows/bazel.yml`) for every Gazebo
package that is part of this Bazel workspace, for each supported
[Gazebo collection](https://gazebosim.org/docs/latest/releases/).

Bazel (bzlmod) support was introduced in Ionic, so the Fortress and Harmonic
collections are not listed here.
Rotary is the rolling collection built from the `main` branches.

Status        | Ionic | Jetty | Rotary
------------- | ----- | ----- | ------
[gz-utils][utils-repo] | [![Bazel CI][utils-ionic-gh-actions-badge]][utils-ionic-gh-actions] | [![Bazel CI][utils-jetty-gh-actions-badge]][utils-jetty-gh-actions] | [![Bazel CI][utils-rotary-gh-actions-badge]][utils-rotary-gh-actions]
[gz-math][math-repo] | [![Bazel CI][math-ionic-gh-actions-badge]][math-ionic-gh-actions] | [![Bazel CI][math-jetty-gh-actions-badge]][math-jetty-gh-actions] | [![Bazel CI][math-rotary-gh-actions-badge]][math-rotary-gh-actions]
[gz-plugin][plugin-repo] | [![Bazel CI][plugin-ionic-gh-actions-badge]][plugin-ionic-gh-actions] | [![Bazel CI][plugin-jetty-gh-actions-badge]][plugin-jetty-gh-actions] | [![Bazel CI][plugin-rotary-gh-actions-badge]][plugin-rotary-gh-actions]
[gz-common][common-repo] | [![Bazel CI][common-ionic-gh-actions-badge]][common-ionic-gh-actions] | [![Bazel CI][common-jetty-gh-actions-badge]][common-jetty-gh-actions] | [![Bazel CI][common-rotary-gh-actions-badge]][common-rotary-gh-actions]
[gz-msgs][msgs-repo] | [![Bazel CI][msgs-ionic-gh-actions-badge]][msgs-ionic-gh-actions] | [![Bazel CI][msgs-jetty-gh-actions-badge]][msgs-jetty-gh-actions] | [![Bazel CI][msgs-rotary-gh-actions-badge]][msgs-rotary-gh-actions]
[gz-rendering][rendering-repo] | [![Bazel CI][rendering-ionic-gh-actions-badge]][rendering-ionic-gh-actions] | [![Bazel CI][rendering-jetty-gh-actions-badge]][rendering-jetty-gh-actions] | [![Bazel CI][rendering-rotary-gh-actions-badge]][rendering-rotary-gh-actions]
[sdformat][sdformat-repo] | [![Bazel CI][sdformat-ionic-gh-actions-badge]][sdformat-ionic-gh-actions] | [![Bazel CI][sdformat-jetty-gh-actions-badge]][sdformat-jetty-gh-actions] | [![Bazel CI][sdformat-rotary-gh-actions-badge]][sdformat-rotary-gh-actions]
[gz-fuel-tools][fuel-tools-repo] | [![Bazel CI][fuel-tools-ionic-gh-actions-badge]][fuel-tools-ionic-gh-actions] | [![Bazel CI][fuel-tools-jetty-gh-actions-badge]][fuel-tools-jetty-gh-actions] | [![Bazel CI][fuel-tools-rotary-gh-actions-badge]][fuel-tools-rotary-gh-actions]
[gz-transport][transport-repo] | [![Bazel CI][transport-ionic-gh-actions-badge]][transport-ionic-gh-actions] | [![Bazel CI][transport-jetty-gh-actions-badge]][transport-jetty-gh-actions] | [![Bazel CI][transport-rotary-gh-actions-badge]][transport-rotary-gh-actions]
[gz-sensors][sensors-repo] | [![Bazel CI][sensors-ionic-gh-actions-badge]][sensors-ionic-gh-actions] | [![Bazel CI][sensors-jetty-gh-actions-badge]][sensors-jetty-gh-actions] | [![Bazel CI][sensors-rotary-gh-actions-badge]][sensors-rotary-gh-actions]
[gz-physics][physics-repo] | [![Bazel CI][physics-ionic-gh-actions-badge]][physics-ionic-gh-actions] | [![Bazel CI][physics-jetty-gh-actions-badge]][physics-jetty-gh-actions] | [![Bazel CI][physics-rotary-gh-actions-badge]][physics-rotary-gh-actions]
[gz-sim][sim-repo] | [![Bazel CI][sim-ionic-gh-actions-badge]][sim-ionic-gh-actions] | [![Bazel CI][sim-jetty-gh-actions-badge]][sim-jetty-gh-actions] | [![Bazel CI][sim-rotary-gh-actions-badge]][sim-rotary-gh-actions]

## Collections and versions

Branch (and major version) tracked by each column above.

Package       | Ionic | Jetty | Rotary
------------- | ----- | ----- | ------
[gz-utils][utils-repo] | `gz-utils3` | `gz-utils4` | `main` (5)
[gz-math][math-repo] | `gz-math8` | `gz-math9` | `main` (10)
[gz-plugin][plugin-repo] | `gz-plugin3` | `gz-plugin4` | `main` (5)
[gz-common][common-repo] | `gz-common6` | `gz-common7` | `main` (8)
[gz-msgs][msgs-repo] | `gz-msgs11` | `gz-msgs12` | `main` (13)
[gz-rendering][rendering-repo] | `gz-rendering9` | `gz-rendering10` | `main` (11)
[sdformat][sdformat-repo] | `sdf15` | `sdf16` | `main` (17)
[gz-fuel-tools][fuel-tools-repo] | `gz-fuel-tools10` | `gz-fuel-tools11` | `main` (12)
[gz-transport][transport-repo] | `gz-transport14` | `gz-transport15` | `main` (16)
[gz-sensors][sensors-repo] | `gz-sensors9` | `gz-sensors10` | `main` (11)
[gz-physics][physics-repo] | `gz-physics8` | `gz-physics9` | `main` (10)
[gz-sim][sim-repo] | `gz-sim9` | `gz-sim10` | `main` (11)

The following packages of the collections are not built by this workspace, since
they have no Bazel support: `gz-gui`, `gz-launch` and `gz-tools`.
`gz-cmake` is not needed, its role is taken by
[rules_gazebo](https://github.com/gazebo-tooling/rules_gazebo).

[utils-repo]: https://github.com/gazebosim/gz-utils
[utils-ionic-gh-actions]: https://github.com/gazebosim/gz-utils/actions/workflows/bazel.yml?query=branch%3Agz-utils3
[utils-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-utils/actions/workflows/bazel.yml/badge.svg?branch=gz-utils3
[utils-jetty-gh-actions]: https://github.com/gazebosim/gz-utils/actions/workflows/bazel.yml?query=branch%3Agz-utils4
[utils-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-utils/actions/workflows/bazel.yml/badge.svg?branch=gz-utils4
[utils-rotary-gh-actions]: https://github.com/gazebosim/gz-utils/actions/workflows/bazel.yml?query=branch%3Amain
[utils-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-utils/actions/workflows/bazel.yml/badge.svg?branch=main

[math-repo]: https://github.com/gazebosim/gz-math
[math-ionic-gh-actions]: https://github.com/gazebosim/gz-math/actions/workflows/bazel.yml?query=branch%3Agz-math8
[math-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-math/actions/workflows/bazel.yml/badge.svg?branch=gz-math8
[math-jetty-gh-actions]: https://github.com/gazebosim/gz-math/actions/workflows/bazel.yml?query=branch%3Agz-math9
[math-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-math/actions/workflows/bazel.yml/badge.svg?branch=gz-math9
[math-rotary-gh-actions]: https://github.com/gazebosim/gz-math/actions/workflows/bazel.yml?query=branch%3Amain
[math-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-math/actions/workflows/bazel.yml/badge.svg?branch=main

[plugin-repo]: https://github.com/gazebosim/gz-plugin
[plugin-ionic-gh-actions]: https://github.com/gazebosim/gz-plugin/actions/workflows/bazel.yml?query=branch%3Agz-plugin3
[plugin-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-plugin/actions/workflows/bazel.yml/badge.svg?branch=gz-plugin3
[plugin-jetty-gh-actions]: https://github.com/gazebosim/gz-plugin/actions/workflows/bazel.yml?query=branch%3Agz-plugin4
[plugin-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-plugin/actions/workflows/bazel.yml/badge.svg?branch=gz-plugin4
[plugin-rotary-gh-actions]: https://github.com/gazebosim/gz-plugin/actions/workflows/bazel.yml?query=branch%3Amain
[plugin-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-plugin/actions/workflows/bazel.yml/badge.svg?branch=main

[common-repo]: https://github.com/gazebosim/gz-common
[common-ionic-gh-actions]: https://github.com/gazebosim/gz-common/actions/workflows/bazel.yml?query=branch%3Agz-common6
[common-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-common/actions/workflows/bazel.yml/badge.svg?branch=gz-common6
[common-jetty-gh-actions]: https://github.com/gazebosim/gz-common/actions/workflows/bazel.yml?query=branch%3Agz-common7
[common-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-common/actions/workflows/bazel.yml/badge.svg?branch=gz-common7
[common-rotary-gh-actions]: https://github.com/gazebosim/gz-common/actions/workflows/bazel.yml?query=branch%3Amain
[common-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-common/actions/workflows/bazel.yml/badge.svg?branch=main

[msgs-repo]: https://github.com/gazebosim/gz-msgs
[msgs-ionic-gh-actions]: https://github.com/gazebosim/gz-msgs/actions/workflows/bazel.yml?query=branch%3Agz-msgs11
[msgs-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-msgs/actions/workflows/bazel.yml/badge.svg?branch=gz-msgs11
[msgs-jetty-gh-actions]: https://github.com/gazebosim/gz-msgs/actions/workflows/bazel.yml?query=branch%3Agz-msgs12
[msgs-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-msgs/actions/workflows/bazel.yml/badge.svg?branch=gz-msgs12
[msgs-rotary-gh-actions]: https://github.com/gazebosim/gz-msgs/actions/workflows/bazel.yml?query=branch%3Amain
[msgs-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-msgs/actions/workflows/bazel.yml/badge.svg?branch=main

[rendering-repo]: https://github.com/gazebosim/gz-rendering
[rendering-ionic-gh-actions]: https://github.com/gazebosim/gz-rendering/actions/workflows/bazel.yml?query=branch%3Agz-rendering9
[rendering-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-rendering/actions/workflows/bazel.yml/badge.svg?branch=gz-rendering9
[rendering-jetty-gh-actions]: https://github.com/gazebosim/gz-rendering/actions/workflows/bazel.yml?query=branch%3Agz-rendering10
[rendering-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-rendering/actions/workflows/bazel.yml/badge.svg?branch=gz-rendering10
[rendering-rotary-gh-actions]: https://github.com/gazebosim/gz-rendering/actions/workflows/bazel.yml?query=branch%3Amain
[rendering-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-rendering/actions/workflows/bazel.yml/badge.svg?branch=main

[sdformat-repo]: https://github.com/gazebosim/sdformat
[sdformat-ionic-gh-actions]: https://github.com/gazebosim/sdformat/actions/workflows/bazel.yml?query=branch%3Asdf15
[sdformat-ionic-gh-actions-badge]: https://github.com/gazebosim/sdformat/actions/workflows/bazel.yml/badge.svg?branch=sdf15
[sdformat-jetty-gh-actions]: https://github.com/gazebosim/sdformat/actions/workflows/bazel.yml?query=branch%3Asdf16
[sdformat-jetty-gh-actions-badge]: https://github.com/gazebosim/sdformat/actions/workflows/bazel.yml/badge.svg?branch=sdf16
[sdformat-rotary-gh-actions]: https://github.com/gazebosim/sdformat/actions/workflows/bazel.yml?query=branch%3Amain
[sdformat-rotary-gh-actions-badge]: https://github.com/gazebosim/sdformat/actions/workflows/bazel.yml/badge.svg?branch=main

[fuel-tools-repo]: https://github.com/gazebosim/gz-fuel-tools
[fuel-tools-ionic-gh-actions]: https://github.com/gazebosim/gz-fuel-tools/actions/workflows/bazel.yml?query=branch%3Agz-fuel-tools10
[fuel-tools-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-fuel-tools/actions/workflows/bazel.yml/badge.svg?branch=gz-fuel-tools10
[fuel-tools-jetty-gh-actions]: https://github.com/gazebosim/gz-fuel-tools/actions/workflows/bazel.yml?query=branch%3Agz-fuel-tools11
[fuel-tools-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-fuel-tools/actions/workflows/bazel.yml/badge.svg?branch=gz-fuel-tools11
[fuel-tools-rotary-gh-actions]: https://github.com/gazebosim/gz-fuel-tools/actions/workflows/bazel.yml?query=branch%3Amain
[fuel-tools-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-fuel-tools/actions/workflows/bazel.yml/badge.svg?branch=main

[transport-repo]: https://github.com/gazebosim/gz-transport
[transport-ionic-gh-actions]: https://github.com/gazebosim/gz-transport/actions/workflows/bazel.yml?query=branch%3Agz-transport14
[transport-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-transport/actions/workflows/bazel.yml/badge.svg?branch=gz-transport14
[transport-jetty-gh-actions]: https://github.com/gazebosim/gz-transport/actions/workflows/bazel.yml?query=branch%3Agz-transport15
[transport-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-transport/actions/workflows/bazel.yml/badge.svg?branch=gz-transport15
[transport-rotary-gh-actions]: https://github.com/gazebosim/gz-transport/actions/workflows/bazel.yml?query=branch%3Amain
[transport-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-transport/actions/workflows/bazel.yml/badge.svg?branch=main

[sensors-repo]: https://github.com/gazebosim/gz-sensors
[sensors-ionic-gh-actions]: https://github.com/gazebosim/gz-sensors/actions/workflows/bazel.yml?query=branch%3Agz-sensors9
[sensors-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-sensors/actions/workflows/bazel.yml/badge.svg?branch=gz-sensors9
[sensors-jetty-gh-actions]: https://github.com/gazebosim/gz-sensors/actions/workflows/bazel.yml?query=branch%3Agz-sensors10
[sensors-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-sensors/actions/workflows/bazel.yml/badge.svg?branch=gz-sensors10
[sensors-rotary-gh-actions]: https://github.com/gazebosim/gz-sensors/actions/workflows/bazel.yml?query=branch%3Amain
[sensors-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-sensors/actions/workflows/bazel.yml/badge.svg?branch=main

[physics-repo]: https://github.com/gazebosim/gz-physics
[physics-ionic-gh-actions]: https://github.com/gazebosim/gz-physics/actions/workflows/bazel.yml?query=branch%3Agz-physics8
[physics-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-physics/actions/workflows/bazel.yml/badge.svg?branch=gz-physics8
[physics-jetty-gh-actions]: https://github.com/gazebosim/gz-physics/actions/workflows/bazel.yml?query=branch%3Agz-physics9
[physics-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-physics/actions/workflows/bazel.yml/badge.svg?branch=gz-physics9
[physics-rotary-gh-actions]: https://github.com/gazebosim/gz-physics/actions/workflows/bazel.yml?query=branch%3Amain
[physics-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-physics/actions/workflows/bazel.yml/badge.svg?branch=main

[sim-repo]: https://github.com/gazebosim/gz-sim
[sim-ionic-gh-actions]: https://github.com/gazebosim/gz-sim/actions/workflows/bazel.yml?query=branch%3Agz-sim9
[sim-ionic-gh-actions-badge]: https://github.com/gazebosim/gz-sim/actions/workflows/bazel.yml/badge.svg?branch=gz-sim9
[sim-jetty-gh-actions]: https://github.com/gazebosim/gz-sim/actions/workflows/bazel.yml?query=branch%3Agz-sim10
[sim-jetty-gh-actions-badge]: https://github.com/gazebosim/gz-sim/actions/workflows/bazel.yml/badge.svg?branch=gz-sim10
[sim-rotary-gh-actions]: https://github.com/gazebosim/gz-sim/actions/workflows/bazel.yml?query=branch%3Amain
[sim-rotary-gh-actions-badge]: https://github.com/gazebosim/gz-sim/actions/workflows/bazel.yml/badge.svg?branch=main
