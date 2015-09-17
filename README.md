# alloc_system3ds

Simplified allocator implementation for Rust on the Nintendo 3DS.

## Using

Make sure your sysroot for 3DS doesn't contain liballoc_system from anything else. Then, add this repo as a dependency in Cargo.

  [dependencies.alloc_system3ds]
  git = "https://github.com/Furyhunter/alloc_system3ds"

## Known issues

 * Doesn't leverage linear memory at all. Entirely depends on malloc impl provided.
 * Not well tested.
