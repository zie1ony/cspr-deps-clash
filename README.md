```bash
cargo check

    Updating git repository `https://github.com/casper-network/casper-node.git`
    Updating crates.io index
error: failed to select a version for `schemars`.
    ... required by package `casper-execution-engine v7.0.1 (https://github.com/casper-network/casper-node.git?branch=feat-2.0#ee9c6de3)`
    ... which satisfies git dependency `casper-execution-engine-condor` of package `deps-test v0.1.0 (/Users/ziel/workspace/odra/deps-test)`
versions that meet the requirements `^0.8.16` are: 0.8.21, 0.8.20, 0.8.19, 0.8.18, 0.8.17, 0.8.16

all possible versions conflict with previously selected packages.

  previously selected package `schemars v0.8.5`
    ... which satisfies dependency `schemars = "=0.8.5"` (locked to 0.8.5) of package `casper-execution-engine v7.0.1`
    ... which satisfies dependency `casper-execution-engine = "^7.0.1"` (locked to 7.0.1) of package `deps-test v0.1.0 (/Users/ziel/workspace/odra/deps-test)`

failed to select a version for `schemars` which could resolve this conflict
```