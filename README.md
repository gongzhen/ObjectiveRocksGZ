# ObjectiveRocksGZ

# Quick Overview

RocksDB is a key-value store, where the keys and values are arbitrarily-sized byte streams. The keys are ordered within the key value store according to a specified comparator function. RocksDB supports atomic reads and writes, snapshots, iteration and features many configuration options.

# Installation

## Manually

1- Add `ObjectiveRocksGZ` as git submodule

```bash
$ git submodule add https://github.com/iabudiab/ObjectiveRocks.git
$ git submodule update
```

2- Open the `ObjectiveRocksGZ` folder and drag'n'drop the `ObjectiveRocksGZ.xcodeproj` into the Project Navigator in Xcode to add it as a sub-project.

3- In the General panel of your target add `ObjectiveRocksGZ.framework` under the `Embedded Binaries` 

> Notice that ObjectiveRocks depends on RocksDB and includes it as a Git submodule.

# Usage

> The README will use the `NSString` notation in place of `NSData` keys and values for brevity!

